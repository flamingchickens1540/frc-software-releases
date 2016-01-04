# FRC Software Releases
A big list of all the FRC team software releases from recent years!

Want to add something about your code, or don't like how your team's work shows up? Send a pull request!

Also, note that it's not entirely clear that adding your code to this list is sufficient to count as a code release. You are recommended to create a Chief Delphi thread and then add your team's code to this list.

# 2015 season code

## Team 107: R.O.B.O.T.I.C.S (LabVIEW)

>  If you have any questions about what we have done let me know.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137046) | [Robot Code on Dropbox](https://www.dropbox.com/sh/0n8wnv9c8mrd2sk/AADJFHstVXQxbpY_pTD4p-Jaa?dl=0) | [Dashboard Code on Dropbox](https://www.dropbox.com/sh/12waxpw4c6kz68p/AAAQl4qh_KgX-2NQAkhaiV4ka?dl=0)

## Team 174: Arctic Warriors (Java/Command-Based)

> * Java simulator - Unobtrusive "simulator" that can be used with any teams java code. It sounds like we took a similar approach to what team 254 did
> * Custom SmartDashboard widgets - Custom widgets to show robot state, motion profiling state, and our autonomous editor
> * Autonomous Scripting - Command based autonomous scripts. Stored as text files on the robot, can be edited from the SmartDashboard
> * Motion Profiling - I had my students hand roll a simple version for straight paths. We also took team 254's spline library as is.

> In developing our software this year, we tried to have a more structured design process. We made a design notebook for our entire robot which will be released at a later date, including class diagrams and sequence diagram. We used the Agile methodology to develop our software, which worked quite well with the structure of a FIRST season and our constantly changing requirements

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137819) | [Robot Code on GitHub] (https://github.com/ArcticWarriors/snobot2015) | [PDF](https://github.com/ArcticWarriors/snobot2015/raw/master/Team174Software.pdf)

## Team 254: The Cheesy Poofs (Java/WPILib)

> This year’s software includes new features such as a test harness and simulator code to run the program on a computer, web-based graphing tools, constants editor, and autonomous selection, blocking autonomous routines, and a controller that calculates and follows a trapezoidal motion profile, on the fly.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137843) | [Robot Code on GitHub](https://github.com/Team254/FRC-2015) | [Simulated robot hardware on GitHub](https://github.com/Team254/Sim-FRC-2015) | [Simulator on GitHub](https://github.com/tombot/FakeWPILib) | [GitHub](https://github.com/Team254)

## Team 423: Simple Machines (LabVIEW)

> As our robot code approaches its zenith, I wanted to share it with the Chief Delphi community for people to learn from, possibly to get suggestions, and to show the world how the Simple Machines works. Nice and simple; our code is like our machines. Features: autonomous recorder and playback, mecanum driving, pneumatic elevator, and a cool dashboard.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137627) | [Robot Code on Dropbox](https://www.dropbox.com/sh/ock70bamdmtwp24/AADkortfP3wtt3RPaT1Z3ZTOa?dl=0)

## Team 624: CRyptonite (LabVIEW)

>  This includes a library for using CAN Talons in LabVIEW with limited memory overhead, a scripted autonomous structure and text editor with a customizable programming language, and our version of Smart Dashboard which uses UDP instead of Network Tables. It also contains our offseason RGB lights code.

>  We experimented with Feed Forward and Motion Profiling in the fall. With some tuning, I was able to get our 2015 bot and a kitbot to go any distance I wanted without encoders (within an inch or two). I am still working on the integration with Feedback to make it more accurate and the latest code will be available on Github. This project may not be able to be opened until Kickoff because older versions of LabVIEW do not support projects built under Beta.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140790) | [Robot Code on team website](http://team624.org/files/624%202015%20Code%20Release.zip) | [Robot Code from Beta 2015](http://team624.org/files/624-Feed-Forward-R-D.zip) | [Team Website](http://team624.org/?controller=page&action=programmingResources) | [GitHub](https://github.com/Team624)

## Team 900: Zebracorns (LabVIEW)

> Included is our LabVIEW Swerve Drive and Arm control, our dashboard, and the vision code we used this year on our on board Jetson TK1 to detect the green bins during auton. We will be releasing a few whitepapers in the following month(s) about the systems our robot used this year.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137021) | [Robot Code on GitHub](https://github.com/FRC900/2015RobotCode) | [Dashboard Code on GitHub](https://github.com/FRC900/2015DashboardCode) | [Vision Code on GitHub](https://github.com/FRC900/2015VisionCode) | [Vision Whitepaper on Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?p=1484741)

## Team 971: Spartan Robotics (C++/WPILib)

> * Most of the stuff we modify year-to-year is written in C++ and Python
> * We use Python to design our controllers and generate raw matrices for our state feedback controllers that can be used with the C++ code directly. [Another thread diving into our control system code and theory is available here](http://www.chiefdelphi.com/forums/showthread.php?t=129574)
> * We recently switched from an older build system based mainly on GYP files to Bazel, which is the publicly-available version of Google's build system
> * All robots included in this snapshot (2014 competition robot (Mammoth), 2014 3rd robot (Butterknife), 2015 competition robot (Subzero), and 2015 third robot (Robonauts?)) are up-to-date for the RoboRIO and other 2015 FIRST control system components

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140568) | [Robot Code on team website](http://robotics.mvla.net/spartanrobotics/releases/src/2015_code.tar.gz) | [General software info on team website](http://frc971.org/content/2015-software) | [CAD on Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?threadid=137883) | [Team Website](http://frc971.org/)

## Team 980: Thunderbots

> 2015 was a learning and testing year for the Thunderbots, so you'll see a lot of test codes and not a lot of organization. This season we'll see more organization.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140895) | [Robot Code on GitHub](https://github.com/Team980/2015) | [GitHub](https://github.com/Team980)

## Team 1410: The Kraken (C++/Command-Based)

> You may notice two weird things. The first is the array and method at the top of the OI. These are used to add a dead-zone into the controller, making them less sensitive. The second would be the SimultaneousOp CommandGroups in the IntakeArms and CanManipulator Commands folders. These are used so that we can both drive the rollers/arms, and the elevator/arms simultaneously. We could have had a command for this, but by using a command group we can also use the separate commands outside of it.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=135701) | [Robot Code on GitHub](https://github.com/FRC-Team-1410/RR2015-FRC1410)

## Team 1540: The Flaming Chickens (Java/CCRE)

>  We ran our robot software department on a code-review setup: everything got developed in a separate branch, pull-requested, and code-reviewed before merge. [You can see the log of this on the project page.](https://github.com/flamingchickens1540/quasar-helios-2015/pulls?q=is%3Apr+is%3Aclosed) 107 pull requests!
> This ended up working really well for us - it allowed us to edit each other's code to be higher quality in a way that gave everyone rapid feedback and allowed team members to become much better programmers over the course of the season.
>
> (Also, for reference, our code uses [the Common Chicken Runtime Engine](http://www.chiefdelphi.com/forums/showthread.php?t=130813), our dataflow-based robot code framework, which should explain some of the nonstandard coding.)
> 
> One other thing that helped: multi-layered autonomous modes. Some of our modes would pick up totes. To do this, they would start the pseudo-autonomous mode for autoloading (which was also used by the drivers), which would, in turn, also start the pseudo-autonomous mode for automatically controlling the elevator stacking sequence (also available to the drivers separately.)

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137255) | [Robot Code on GitHub](https://github.com/flamingchickens1540/quasar-helios-2015) | [GitHub](https://github.com/flamingchickens1540)

## Team 1701: RoboCubs (Java/Command-Based)

> This year we used the new AndyMark Swerve Drives.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137028) | [Robot Code on GitHub](https://github.com/bh202548/Robocubs-Code-2015/)

## Team 1756: Argos (LabVIEW)

> As promised here is team 1756 Argos robot code. We did not clean it up so it is a little messy but if anyone has any questions please feel free to ask.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137483) | [Robot Code on Chief Delphi](http://www.chiefdelphi.com/media/papers/3152?)

## Team 1768: Robochiefs (Java/Command-Based)

> 2015's code features code to connect to an arduino over ethernet, PID with feed forward, and more.

[Robot Code on GitHub](https://github.com/Nashoba-Robotics/Nashoba-Robotics2015) | [Ardunio Code on GitHub](https://github.com/Nashoba-Robotics/CoffinLED) | [GitHub](https://github.com/Nashoba-Robotics)

## Team 1939: Kuhnigits (Java/Command-Based)

> This year was exciting for the programming team. New control techniques such as PID were explored, and new Talon SRX speed controllers made programming and wiring easier. Our team believes heavily in the WPILib programming model of Subsystems and Commands. All of our code follows this Command Based model.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=139606) | [Robot Code on GitHub](https://github.com/FIRST1939/RecycleRush2015)

## Team 2062: C.O.R.E 2062 (C++/WPILib)

>  This year we added a better way of examining match data by putting match data onto a file that we can look on after a match. We also experimented heavily with PID and added some functionality in the library to compliment it in the future. Lastly we tried to find a better way to manage the smartdashboard but it is currently incomplete and will most likely be finished in the of season. Other than that there were a few minor tweaks and additions.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=123909) | [Robot Code on GitHub](https://github.com/core2062/CORE2015/)

## Team 2067: Apple PI (LabVIEW)

> The most interesting parts are the Swerve Drive folder, and the AppleScript folder. AppleScript is a scripting language that is used to rapidly develop autonomous code, and is then executed by an interpreter in LabVIEW. The script is stored on the driver station computer, and is sent to the robot over network tables whenever an update is made.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140820) | [Robot Code on GitHub](https://github.com/applepi-2067/Robot-2015) | [Swerve Drive Powerpoint on Google Drive](https://drive.google.com/open?id=0Byip7vBcYbKmY3lzdEJiclpMRTQ)

## Team 2084: Robots by the C (Java/Command-Based)

> * Flexible drive system that makes it easy to implement different drive systems. The mecanum code features support for gyros and wheel encoders, but not everything is fully tested.
> * ParameterCommand - allows Commands to have parameters that can be set from the SmartDashboard.
> * State machines to control other robot subsystems.
> * Semi-functional driver for the ITG3200 gyro (we didn't use it).
> * Slider - a simple slider control, something that is missing from the built in widgets.
> * ParameterCommand - widget that displays the parameters from a ParameterCommand on the robot
> * WheelController - Used in conjunction with our drive code to display throttle, current and other values from our motors.
> * VideoServer - allows for streaming of any OpenCV image over http as an mjpg. It could probably use some improvement, but it works okay. It was ported from a (non-FRC) C++ version I wrote earlier, which I released [here](http://www.chiefdelphi.com/forums/showpost.php?p=1438448&postcount=36), in case anyone wants to see it.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=136411) | [Robot Code on GitHub](https://github.com/RobotsByTheC/CMonster2015) | [SmartDashboard Extensions on GitHub](https://github.com/RobotsByTheC/SmartDashboardExtensions2015) | [Vision Processor on GitHub](https://github.com/RobotsByTheC/VisionProcessor2015) | [GitHub](https://github.com/RobotsByTheC)

## Team 2122: Team Tators (C++/Command-Based)

> As one of our seniors put it, "Wow this is some cool code for you!" I couldn't have put it more eloquently.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137296) | [Robot Code on GitHub](https://github.com/Team2122/Kartoshka)

## Team 2363: Triple Helix (Java/Command-Based)

> This was definitely our most complex robot to date. Comments and questions welcome.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=137180) | [Robot Code on GitHub](https://github.com/TripleHelixProgramming/recycle-rush/tree/working_branch) | [GitHub](https://github.com/TripleHelixProgramming)

## Team 2481: Roboteers (C++/Command-Based)

> A couple things we would like to call out are the 3 tote autonomous sequence and our fully autonomous stacker. We attribute much of our success to our automated sequences that allowed the drivers to focus on playing the game at a higher level.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=138077) | [Robot Code on GitHub](https://github.com/Frc2481/frc-2015)

## Team 2485: WARLords (Java/WPILib)

> Our Sequencer Factory class enabled us to rapidly create and modify auto sequences, which could also be used in teleop.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=136899) | [Robot Code on GitHub](https://github.com/team2485/frc-2015)

## Team 2614: MARS (LabVIEW)

> Of note in this code is our autonomous play infrastructure which is described in the attached document. In summary, the infrastructure uses parameterized commands to develop autonomous plays. Once the basic commands are created, no further modifications to robot code are needed. An external labview application runs on a separate laptop or the driver station laptop. This application connects to the robot and reads the available commands. You then build plays using the commands and adding values for the parameters. Commands can be run sequentially or indicated to be run concurrently. Each play is a separate file stored on the robot which can then be selected from a pulldown menu in the DS. Plays can be rapidly modified and rerun (like on a practice field) because no code deployment is needed.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140812) | [Document on Chief Delphi](http://www.chiefdelphi.com/forums/attachment.php?attachmentid=19617&d=1451782809) | [Robot Code on Chief Delphi](http://www.chiefdelphi.com/forums/attachment.php?attachmentid=19618&d=1451784369) | [Dashboard Code on Chief Delphi](http://www.chiefdelphi.com/forums/attachment.php?attachmentid=19619&d=1451784383)

## Team 2729: Storm Robotics Team (Java/Command-Based)

> Hello! I am a member of Storm Team 2729. I am making our 2015 season's code available to the public.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=136873) | [Robot Code on GitHub](https://github.com/2729StormRobotics/Storm2015) | [Arduino LED Code on GitHub](https://github.com/2729StormRobotics/StormArduino2015) | [Vision Code on GitHub](https://github.com/2729StormRobotics/Storm2015CV) | [GitHub](https://github.com/2729StormRobotics)

## Team 3019: Firebirds (Java/Command-Based)

> I have decided to post our robot code on cd. Our robot has 4 encoders with an H omni wheel drive. We have a elevator on the front and a pneumatic claw and elevator on the rear.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=135459) | [Robot Code on GitHub](https://github.com/fauge7/Gainz-Robot-Code/tree/master/Gainz/src/org/usfirst/frc/team3019/robot) | [Website](http://www.firebirdrobotics.com/)

## Team 3081: Kennedy RoboEagles (C++/Command-Based)

> There are several good examples of combining state machines with the Command-Based Robot framework.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140791) | [Robot Code on GitHub](https://github.com/KennedyRoboEagles/PublicRobotCode)

## Team 3322: Eagle Imperium (C++/Command-Based)

> If you have any questions about any of our code, feel free to ask.  Apologies for the messyness of the source, our branches are kinda screwy right now, but WIP_secret_weapon is our main code branch.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140864) | [Robot Code on GitHub](https://github.com/FRC3322/FinalRobot2015)

## Team 3467: The Windham Windup (Java/Command-Based)

> Typical FRC code, just as WPI likes it. There are a few neat features that we added at competitions to meet our needs:

> The 2015 code has a feature where it will not report that the code has "started" until we see that the smart dashboard has connected - which picks our autonomous mode. We accomplish this by extending IterativeRobot.class (ours is IterativeRobotCustom) and not executing the line that tells the FMS the code has started (FRC.ObserveUserProgramStarting()) until we receive a user's click on a smart dashboard item.

> Also, the 2015 code will crash the code (throws an exception) if the driver's joystick calibrates improperly. When this happens, the LED strip on the driver console lights up bright red and the user needs to restart the code and recalibrate the stick (unplug and plug back in, hit F1). This code also has an implementation of the [PulsedLight LIDAR-lite](https://engineering.purdue.edu/477grp7/datasheets/lidar.pdf) module, and changes the colors of the driver station LEDs according to the distance, which helps us line up at the human feeder station.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140853) | [Robot Code on GitHub](https://github.com/WHS-FRC-3467/Skip-5.5) | [GitHub](https://github.com/whs-frc-3467)

## Team 3620: The Average Joes (Java/Command-Based)

> Most of the code is pretty typical FRC code (complete with warts). There are a few unusual things in there, though, that other teams may find useful:
> 
> * event logging.
> * data logging.
> * UDP transmission of JSON encoded data to an onboard co-processor.
> * UDP reception of JSON encoded data from an onboard co-processor.
> * adding third party jars to the build.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140729) | [Robot Code on GitHub](https://github.com/FRC3620/FRC3620_2015_AverageJava) | [White paper](http://www.chiefdelphi.com/media/papers/3189)

## Team 4480: UC-Botics (Python)

> This is the first year we used Python as the primary programming of the robot. The code is pretty basic for our lifter, but the code provides a decent template for future teams to try Python. We had a good experience with it because of the support of the developers of RobotPy.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140861) | [Robot Code on GitHub](https://github.com/bb20basketball/2015-Team4480-Code/)

## Team 4561: TerrorBytes (Java/Command-Based)

> Our robot has a mecanum drive train, an elevator, a telescoping arm, and a pneumatic claw. This is its code.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=138078) | [Robot Code on GitHub](https://github.com/Terrorbytes/TB2015)

## Team 4901: Garnet Squadron (LabVIEW)

> * No old code yet, except a port of last years robot code from Java (not available) to LabVIEW. 
> * The projects directory has some design stuff (schematic, firmware, and LabVIEW code) about the control board that's being developed to make it easier to add a custom operator interface for the robot. 
> * We're participating in the Robot In 3 Days project. The code for that project will be available in 2016/Ri3d.

[Chief Delphi](http://www.chiefdelphi.com/forums/showthread.php?t=140892) | [Robot Code on GitHub](https://github.com/ryannazaretian/FRC-4901-Garnet-Squadron) | [Team Website](http://garnetsquadron.com/)
