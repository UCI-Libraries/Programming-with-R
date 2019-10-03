UCI Libraries Digital Scholarship Services

Tuesday November 19, 2019 & Thursday November 21, 2019

2:00 PM - 5:00 PM

Instructor(s): Danielle Kane
Helper(s): Mitchell Brown

<b><a href="https://www.eventbrite.com/e/uci-libraries-programming-with-r-tickets-71086127521">REGISTER HERE</a></b>

Please Note: You must be a UCI affiliate to register, please contact kaned@uci.edu if you are not a member of the UCI community to see if there is room before registering

**General Information:** R is a programming language and free software environment for statistical computing and graphics supported by the R Foundation for Statistical Computing. The R language is widely used among statisticians and data miners for developing statistical software and data analysis.

**Who:** The course is aimed at graduate students and other researchers, including undergrads, faculty, staff and community members. <b>You don't need to have any previous knowledge of the tools that will be presented at the workshop.</b> 

**Where:** Langson Library Rm 228. Get directions with <a href="https://www.openstreetmap.org/#map=17/33.64745/-117.83871">OpenStreetMap</a> or <a href="https://goo.gl/maps/528F8BGTYvJ2">Google Maps</a>.

**When:** November 19, 2019 & November 21, 2019. <a target="_blank" href="https://calendar.google.com/event?action=TEMPLATE&tmeid=MW5saDdvN2s4aXVxZGxqaXEyNjVtMTBybG9fMjAxOTExMTlUMjIwMDAwWiBrYW5lZEB1Y2kuZWR1&tmsrc=kaned%40uci.edu&scp=ALL"><img border="0" src="https://www.google.com/calendar/images/ext/gc_button1_en.gif">Add to your Google Calendar</a>.

**Requirements:** Participants must bring a laptop with a Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) that they have administrative privileges on. They should have a few specific software packages installed (listed below). 

**Accessibility:** We are committed to making this workshop accessible to everybody. The workshop organisers have checked that:

    The room is wheelchair / scooter accessible.
    Accessible restrooms are available.

Materials will be provided in at the workshop and large-print handouts are available if needed by notifying the organizers in advance. If we can help making learning easier for you (e.g. sign-language interpreters, lactation facilities) please get in touch (using contact details below) and we will attempt to provide them.

**Contact:** Please email Danielle Kane at kaned@uci.edu for more information.

Syllabus: Programming with R

1. Working with vectors and data frames
2. Reading and plotting data
3. Creating and using functions
4. Loops and conditionals
5. Using R from the command line
 
**Setup**

You will need access to the software described below. In addition, you will need an up-to-date web browser.

We maintain a list of common issues that occur during installation as a reference for instructors that may be useful on the Configuration Problems and Solutions wiki page.

**The Bash Shell**

Bash is a commonly-used shell that gives you the power to do simple tasks more quickly. <a href="https://gitforwindows.org">Download the Git for Windows installer</a>.

    Run the installer and follow the steps bellow:
        Click on "Next".
        Click on "Next".
        Keep "Use Git from the Windows Command Prompt" selected and click on "Next". If you forgot to do this programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.
        Click on "Next".
        Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".
        Keep "Use Windows' default console window" selected and click on "Next".
        Click on "Install".
        Click on "Finish".
    If your "HOME" environment variable is not set (or you don't know what this is):
        Open command prompt (Open Start Menu then type cmd and press [Enter])
        Type the following line into the command prompt window exactly as shown:

        setx HOME "%USERPROFILE%"
        Press [Enter], you should see SUCCESS: Specified value was saved.
        Quit command prompt by typing exit then pressing [Enter]

This will provide you with both Git and Bash in the Git Bash program.

Mac OS X: The default shell in all versions of Mac OS X is Bash, so no need to install anything. You access Bash from the Terminal (found in /Applications/Utilities). See the Git installation video tutorial for an example on how to open the Terminal. You may want to keep Terminal in your dock for this workshop.

Linux: The default shell is usually Bash, but if your machine is set up differently you can run it by opening a terminal and typing bash. There is no need to install anything.

**R**

  <p>
    <a href="https://www.r-project.org">R</a> is a programming language
    that is especially powerful for data exploration, visualization, and
    statistical analysis. To interact with R, we use
    <a href="https://www.rstudio.com/">RStudio</a>.
  </p>

  <div class="row">
    <div class="col-md-4">
      <h4 id="r-windows">Windows</h4>
      <a href="https://www.youtube.com/watch?v=q0PjTAylwoU">Video Tutorial</a>
      <p>
        Install R by downloading and running
        <a href="https://cran.r-project.org/bin/windows/base/release.htm">this .exe file</a>
        from <a href="https://cran.r-project.org/index.html">CRAN</a>.
        Also, please install the
        <a href="https://www.rstudio.com/products/rstudio/download/#download">RStudio IDE</a>.
        Note that if you have separate user and admin accounts, you should run the 
        installers as administrator (right-click on .exe file and select "Run as 
        administrator" instead of double-clicking). Otherwise problems may occur later, 
        for example when installing R packages.
      </p>
    </div>
    <div class="col-md-4">
      <h4 id="r-macosx">macOS</h4>
      <a href="https://www.youtube.com/watch?v=5-ly3kyxwEg">Video Tutorial</a>
      <p>
        Install R by downloading and running
        <a href="https://cran.r-project.org/bin/macosx/R-latest.pkg">this .pkg file</a>
        from <a href="https://cran.r-project.org/index.html">CRAN</a>.
        Also, please install the
        <a href="https://www.rstudio.com/products/rstudio/download/#download">RStudio IDE</a>.
      </p>
    </div>
    <div class="col-md-4">
      <h4 id="r-linux">Linux</h4>
      <p>
        You can download the binary files for your distribution
        from <a href="https://cran.r-project.org/index.html">CRAN</a>. Or
        you can use your package manager (e.g. for Debian/Ubuntu
        run <code>sudo apt-get install r-base</code> and for Fedora run
        <code>sudo dnf install R</code>).  Also, please install the
        <a href="https://www.rstudio.com/products/rstudio/download/#download">RStudio IDE</a>.
      </p>
    </div>
  </div>
