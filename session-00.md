# Session 00

## `git` and GitHub

### GitHub Account

We will be using GitHub to store our projects, so you will need an account. Make sure you use an email address you have easy access to, because GitHub does require multifactor authentication. In some cases, school email addresses cannot receive the required setup emails - this includes Athens City Schools emails for students not in high school.

- [ ] Create a [GitHub](https://www.github.com) account if you do not already have one
- [ ] Talk to a mentor (usually Drew) to get added to the GitHub organization (will require your username)
- [ ] Accept the invitation to the organization (you can accept from your email or by looking at your Organizations in GitHub)


### `git`

`git` is a version control system. It allows you to save changes and traverse the history of your code. If you plan on using the command line or the Visual Studio Code interface for managing your changes, it will need to be installed, so it's good to have regardless.

- [ ] Install [git](https://github.com/git-guides/install-git)
- [ ] Set your name in a terminal window: `git config --global user.name "Your NAME as it appears in GitHub"` (note: this is your NAME, not your USER NAME)
- [ ] Set your email in a terminal window: `git config --global user.email "Your EMAIL in GitHub"` (note: this can be ANY email on your GitHub account, including the `noreply` private address)


### GitHub Desktop

One of the easier ways for newcomers to interact with the `git` version control system and GitHub is through GitHub Desktop.

- [ ] Download and install [GitHub Desktop](https://desktop.github.com/download/)
- [ ] Sign into GitHub Desktop

**Note for Windows users**: When using either `git` or GitHub Desktop, make sure your repositories are created OUTSIDE of OneDrive.


## Core FRC Utilities

### WPILib

The core software library is WPILib. It also includes a wide array of tools, including a version of AdvantageScope and Elastic dashboard the distribution of VS Code to use. **Do not use a non-WPILib VS Code install**. This applies to Windows, macOS, and Linux.

- [ ] Install [WPILib](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html). Make sure to use the `Download for this computer only (fastest)` option.

There is a new version of WPILib each season, and there are often mid-season updates. You can always install newer versions alongside older versions, so the upgrade process is straightforward.

**Be aware**: There will be a new version to install around FRC Kickoff in January.
**Be aware**: AdvantageScope and Elastic may have updates beyond those released with WPILib. See below to install them separately.


### FRC Game Tools

The Driver Station application (among others) is included as part of FRC Game Tools. This applies only to Windows, as the package is not available on macOS or Linux. Note that in order to download the FRC Game Tools, you will need to create an account with NI.

- [ ] Install [FRC Game Tools](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/frc-game-tools.html#installing-the-frc-game-tools)

There is a new version of the FRC Game Tools each season, and there are sometimes mid-season updates. Before installing a new season (*e.g.*, going from 2024 to 2025 or 2025 to 2026), you should [uninstall previous versions](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/frc-game-tools.html#uninstall-old-versions-recommended) before installing the new version. You do not need to uninstall to perform a mid-season upgrade (*e.g.*, 2025.1 to 2025.2).

**Be aware**: There will be a new version to install around FRC Kickoff in January that will require uninstalling the previous version.


## Hardware Clients

### REV Hardware Client

The REV Hardware Client is a tool to configure and test hardware components made by REV Robotics. This applies only to Windows, as the package is not available on macOS or Linux.

- [ ] Install [REV Hardware Client](https://docs.revrobotics.com/rev-hardware-client)

This is the same tool used by FTC Teams to manage their REV hardware devices. You can upgrade the application in-place by having it check for updates regularly. There will be updates at the start of the season, including new firmware. There may be additional updates throughout the season.


### Phoenix Tuner X

Phoenix Tuner X is a tool to configure and test hardware components made by CTR Electronics. This software is free in the Microsoft Store and Google Play Store and for purchase in the Mac App Store and iOS App Store. **Do not feel obligated to purchase this software**.

- [ ] Install [Phoenix Tuner X](https://v6.docs.ctr-electronics.com/en/stable/docs/tuner/index.html)

You can upgrade the application in-place by having it check for updates regularly. There will be updates at the start of the season, including new firmware. There may be additional updates throughout the season.


### Limelight Hardware Manager

The Limelight Hardware Manager is a tool to assist in connecting to and configuring Limelight devices. This applies only to Windows, as the package is not available on macOS or Linux.

- [ ] Install [Limelight Hardware Manager](https://docs.limelightvision.io/docs/resources/downloads)

This tool does not receive *regular* updates like the others. As of this writing, the current version is 2.0.


## Other tools

### PathPlanner

PathPlanner is a tool for drawing paths a robot can follow and building autonomous routines around them. This applies to Windows, macOS, and Linux. The tool can be installed from the Microsoft Store or from a release on their GitHub (for non-Windows).

- [ ] Install [PathPlanner GUI](https://pathplanner.dev/gui-getting-started.html)

You can upgrade the application in-place by having it check for updates regularly. There will be updates at the start of the season, including new firmware. There may be additional updates throughout the season.


### AdvantageScope

AdvantageScope is a robot diagnostics, log review/analysis, and data visualization application. It comes installed with WPILib, but **may receive updates** between updates of WPILib. If you find you need an updated version of AdvantageScope beyond what is bundled in WPILib or wish to receive notifications of new updates, you will need to install it yourself.

- [ ] Install the latest **stable** release of [AdvantageScope](https://docs.advantagescope.org/overview/installation)


### Elastic Dashboard

Elastic is a simple and modern dashboard for FRC. It was built with the goal of being a drag & drop dashboard with an easy setup and elegant UI designed for a high pressure competition environment. It comes installed with WPILib, but **may receive updates** between updates of WPILib. If you find you need an updated version of Elastic beyond what is bundled in WPILib, you will need to install it yourself.

- [ ] Install the latest release of [Elastic](https://frc-elastic.gitbook.io/docs/getting-started/installation)