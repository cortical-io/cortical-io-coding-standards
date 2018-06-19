# Cortical.io Coding Standards

Checkstyle is integrated in the Cortical.io build process to ensure adherence to our coding standards. 

The checkstyle configuration and code style is based on [Google's Java Style Guide](https://google.github.io/styleguide/javaguide.html).

# Checkstyle

Checkstyle is a development tool to help programmers write Java code that adheres to a coding standard.

## Installation (IntelliJ)

* Install Checkstyle-IDEA Plugin via Preferences → Editor → Plugins
* Preferences → Other Settings → Checkstyle
  * Select checkstyle version 8.8
  * Select "Only Java sources (including tests) in the "Scan Scope" dropdown
  * Click "Apply"
  * Select "Use a checkstyle file accessible via HTTP" with the raw github URL to [Cortical_io_Checkstyle.xml](https://raw.githubusercontent.com/cortical-io/cortical-io-coding-standards/master/checkstyle/Cortical_io_Checkstyle.xml)

# Code Style

The code style configuration for the IDE. 

## Installation (IntelliJ)

* Preferences → Editor → Code Style
* Click the three settings dots next to Scheme at the top of the page
* Import Scheme → Import IntelliJ IDEA CodeStyle XML
* Choose [formatting/Cortical_io_FormattingStyle.xml](formatting/Cortical_io_FormattingStyle.xml)

# Scalastyle

ScalaStyle (http://www.scalastyle.org) is like Checkstyle but for Scala.

## Installation (IntelliJ)

Use the configuration file:

[scalastyle/Cortical_io_Scalastyle.xml](scalastyle/Cortical_io_Scalastyle.xml)

Copy the config file to your .idea directory of your project or add symlink after cloning this repo:

e.g. `ln -s cortical-io-coding-standards/scalastyle/Cortical_io_Scalastyle.xml`
