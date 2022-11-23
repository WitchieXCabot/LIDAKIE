<center>
<img src='https://cdn.discordapp.com/attachments/884545008869453834/1045049055341981856/LIDAKIE.png' style='border-radius: 50%;' width='350' height='350'/>
</center>

# !!Software yet to release!!
# LIDAKIE - large Image Data Knowledge Investigations and Extractions

The LIDAKIE software is web-based open source software that is used to analyze and understand large and small computationally and experimentally generated data sets. LIDAKIE presents a matrix view of plots and visualization images and provides a responsive way to investigate the data and extract knowledge and understanding from it. Since it is web-based, it runs on any computer or device that can display a web page. It can also be used remotely and securely by using web server software like an Apache HTTP Server.

If you're interested in contributing to LIDAKIE, the [Contributions guide](CONTRIBUTING.md) will help you.

---

- [Getting Started](#getting-started)
  - [Running LIDAKIE](#running-lidakie)
    - [Locally](#locally)
- [Configuration](#configuration)
  - [Adding data](#adding-data)
- [Contributing](#contributing)
- [Contributors](#contributors)

# Getting Started

The fastest and easiest way to get started is to run LIDAKIE locally.

## Running LIDAKIE

Before you start make sure you have installed:

- [NodeJS](https://www.npmjs.com/) that includes `npm`

### Locally

```powershell
$ git clone https://github.com/WitchieXCabot/LIDAKIE.git
$ npm install
$ npm start
```
***Note:*** *If you want/have made changes make sure to run test with* *`npm run test`*

# Configuration

LIDAKIE can be configured using the following options.       Customize LIDAKIE to work with you data set by modifying the <a href="https://github.com/WitchieXCabot/LIDAKIE/blob/gh-pages/LIDAKIE/LIDAKIE_vent_paper.html">LIDAKIE_vent_paper.html</a> file main page, <a href="https://github.com/WitchieXCabot/LIDAKIE/blob/gh-pages/LIDAKIE/setup_LIDAKIE_vent_paper.js">setup_LIDAKIE_vent_paper.js</a> configuration file, and the <code>get_image_root_name_from_cell_column_and_row_names()</code> function in the <a href="https://github.com/WitchieXCabot/LIDAKIE/blob/gh-pages/LIDAKIE/utils_object.js">utils_object.js</a> file for your data set.

LIDAKIE can be used by accessing the HTML, JavaScript, and image files that make up a LIDAKIE wall from a local file system or through a web server such as Apache HTTP Server. Web access can be protected by standard security systems like using https and requiring a valid username and password for access.

## Adding Data

The LIDAKIE software provides three different views of the data – the main image table, the multi-image window, and the single image window. There are many features that enable an analyst to move through the solution matrix, create different views of the results, and zoom in and out on the images to view the results in detail. The solution images are typically saved in jpeg or png formats but can be saved in any format that can be displayed by a browser. The images are accessed by LIDAKIE wall software using a structured file name convention. For example, “_Mach0.1_” and “_Mach1.0_” can be used in the filename to specify different Mach numbers. Utilizing this structure enables the software to fill the LIDAKIE wall views with the desired data. 

# Contributing
Please see the [Contributing Guide](CONTRIBUTING.md).
# Contributors
This project exists thanks to all the people who contribute... we'd love to see your face on this list!