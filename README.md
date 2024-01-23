<p align="center">
    <a href="http://cppcheck.sourceforge.io">
        <img src="images/logo.png" height="100" alt="Cppcheck's logo"/>
    </a>
</p>
<h2 align="center">C/C++ static code anayser</h2>
<p align="center" float="left">
    <a href="https://snapcraft.io/cppcheck">
        <img src="https://snapcraft.io/cppcheck/badge.svg" width="150" height="17" alt="Snapcraft's Version"/>
    </a>
    &nbsp; &nbsp;
    <a href="https://snapcraft.io/cppcheck">
        <img src="https://img.shields.io/ubuntu/v/cppcheck?label=Cppcheck%20in%20the%20Ubuntu%20archive&color=1c8223" height="17" alt="Ubuntu's Version">
    </a>
    &nbsp; &nbsp;
    <a href="https://github.com/iosifache/cppcheck-snap/actions/workflows/test-build.yaml">
        <img src="https://img.shields.io/github/actions/workflow/status/iosifache/cppcheck-snap/test-build.yaml?label=Build%20Status&color=1c8223" height="17" alt="GitHub Build Workflow Status">
    </a>
</p>

# Description

Cppcheck is a static analysis tool for discovering bugs in C and C++ codebases, even when a non-standard syntax is used.

By implementing coding standards such as Mistra C 2012 and providing extensibility with custom rules, it detects dangerous coding constructs such as buffer overflows, NULL pointer dereferences, and divisions by zero. At the same time, Cppcheck tries to minimise the false positive rates.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/cppcheck)

> Notice: If you want to view the officially recommended method of installing of the tool, refer to the [Cppcheck documentation](https://cppcheck.sourceforge.io/#download).

The goal of this repository is to package Cppcheck as a community snap that can be effortlessly installed across a variety of Linux distributions.

# Local Build

1. Clone this repository: `git clone https://github.com/iosifache/cppcheck-snap`
2. Move into the cloned repository: `cd cppcheck-snap`
3. Install Snapcraft: `sudo snap install snapcraft --classic`
4. Build the snap: `snapcraft --verbose`
5. Install the snap: `snap install --dangerous ./cppcheck_*.snap`
6. Test the snap by running the `cppcheck` command: `cppcheck`

