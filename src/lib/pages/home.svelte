<script lang="ts">
    import Card from "../../card.svelte";
    import WorkHistory from "../work/work-history.svelte";
    import WorkDetail from "../work/work-detail.svelte";
</script>

<div class="container-fluid" style="padding:0px;">
    <div class="col-sm-6 col-xs-12" id="leftCol"> 
        <Card name="😁 About Me" desc="Everyone has a story to tell!" id="#about">
            <div class="container-fluid col-xs-12 text-left">
                <p>
                    Hello! My name is Kyle!<br /><br />
                    Currently I'm in southeast Michigan, and during the week I make my way out to Detroit to work at Rocket Homes!<br /> 
                    As a Software Engineer there, I'm a full stack developer currently doing Android development.<br /><br />
                    I graduated with my Bachelor of Science degree in Computer Science from Eastern Michigan University!
                    During my time at EMU, I did some pretty cool stuff! I worked for the campus Housing &amp; Residence Life program there as an RA. 
                    I was also apart of Kick and Push Longboarding Club, made the dean's list 6 times, and graduated magna cum laude with a 3.74 cumulative GPA.<br /><br />
                    I've always been very passionate about computers, and I love developing software!
                    I find it really interesting to see how things work together through the entire stack! 
                    I primarily learned Java while at EMU, and I began teaching myself C# and web front-end during my free time prior to graduation.
                    I've since gained lots of experience with TypeScript and Angular, as well as .NET Core and WPF/UWP Development.
                    I've also had some experience developing for Android and iOS, and those were some of my favorite projects while at EMU!
                    Since joining up with the Android team at Rocket Homes, this is what I'm more familiar with in terms of mobile development.  
                    Additionally, I also have some experience developing video games in Unity.<br /><br />
                    If you have any questions, please feel free to email me!
                </p>
            </div>
        </Card>
        <Card name="💻 Work History" desc="Oh man, look at the places I've been!" id="#workHist" titleAlign="center">
            <div class="text-left">
                <WorkHistory position="Software Engineer" company="Rocket Homes" location="Detroit, MI" startTime="August 2019">
                    <WorkDetail>
                        Working on Rocket Homes Android app utilizing Kotlin, Android Jetpack components.
                        Integrated Google Play In-App Update and Reviews APIs into app.
                        Converted dependency injection for app from Dagger to Hilt.
                        Leading efforts adopting Jetpack Compose into app.
                        Conducting code reviews.
                    </WorkDetail>
                    <WorkDetail>
                        Workied on Rocket HQ web application utilizing Angular. Added library to enable gestures on the web!
                        Wrote unit tests in Jasmine for various components, services, pipes, and directives for application
                    </WorkDetail>
                    <WorkDetail>
                        Extracted portion of the Rocket HQ web app to expose through an npm module for other team members to use. Provided
                        a component and service, and testing stubs through a module to publish on a JFrog Artifactory npm repository. Made
                        repository containing the code open for others to contribute to.
                    </WorkDetail>
                    <WorkDetail>
                        Developed an internal Android app with Kotlin implementing the single activity multi fragment architecture using Android Jetpack
                        components (Navigation, ViewModels, DataBinding, CameraX, etc.) to create a system for checking out mobile devices for our team.
                        Created backend with Firebase using Cloud Firestore, Cloud Functions, and Authentication for storing data for the app.
                        Created unit tests using Mockito.
                    </WorkDetail>
                    <WorkDetail>
                        Revamped CI strategy with custom JavaScript GitHub Action to keep multiple branches in sync. Maintained clean repo, and streamlined processes using GitHub Actions.
                        <br />
                        <br />
                        <b><u>Technologies Used</u></b>
                        <br />
                        <div class="icon-container">
                            <i class="devicon-android-plain colored workHistIcon"></i>
                            <i class="devicon-kotlin-plain colored workHistIcon"></i>
                            <i class="devicon-gradle-plain colored workHistIcon"></i>
                            <i class="devicon-firebase-plain colored workHistIcon"></i>
                            <i class="devicon-google-plain colored workHistIcon"></i>
                            <i class="devicon-angularjs-plain colored workHistIcon"></i>
                            <i class="devicon-typescript-plain colored workHistIcon"></i>
                            <i class="devicon-jasmine-plain colored workHistIcon"></i>
                            <i class="devicon-sass-plain colored workHistIcon"></i>
                            <i class="devicon-html5-plain colored workHistIcon"></i>
                            <i class="devicon-bootstrap-plain colored workHistIcon"></i>
                            <i class="devicon-nodejs-plain colored workHistIcon"></i>
                            <i class="devicon-github-plain colored workHistIcon"></i>
                            <i class="devicon-figma-plain colored workHistIcon"></i>
                        </div>
                    </WorkDetail>
                </WorkHistory>
                <WorkHistory position="Software Engineer" company="Daifuku" location="Novi, MI" startTime="May 2016" endTime="August 2019">
                    <WorkDetail>
                        Built web applications utilizing Angular, TypeScript, C# .NET Core, and MSSQL to create progressive web apps (PWA).
                        Led Angular front-end development. Built C# .NET Core backend. By developing PWAs for these products, these allowed
                        the apps to perform better on a variety of different devices. Build times were improved, and the apps were able to make
                        use of service workers which allows the apps to be stored on devices for offline use and prompted users to install the
                        apps locally if they liked. Service workers also allowed the Push API to be used so push notifications can be received on 
                        all devices connected to the server.
                    </WorkDetail>
                    <WorkDetail>
                        Created C# WPF Applications to be used for setup of systems utilizing the PWAs. These apps allowed users to configure
                        additional features for the web apps without creating errors in the raw JSON files. This allowed systems to be setup
                        with more ease and automation, and reduced the amount of time technicans spend setting up systems.
                    </WorkDetail>
                    <WorkDetail>
                        Developed an Electron app to be used standalone by internal system engineers to save them time deploying systems on site.
                        This app wraps a portion of one the Angular apps through Electron to be used as a cross-platform desktop app. The app exports
                        a JSON file which can then be imported into the corresponding Angular app.
                    </WorkDetail>
                    <WorkDetail>
                        Assisted in managing local GitLab server. Trained engineers on how to use Git for version control. Assisted engineers with
                        questions on using Git, and specifics with using GitLab.
                        <br />
                        <br />
                        <b><u>Technologies Used</u></b>
                        <br />
                        <div class="icon-container">
                            <i class="devicon-angularjs-plain colored workHistIcon"></i>
                            <i class="devicon-typescript-plain colored workHistIcon"></i>
                            <i class="devicon-nodejs-plain colored workHistIcon"></i>
                            <i class="devicon-csharp-plain colored workHistIcon"></i>
                            <i class="devicon-cplusplus-plain colored workHistIcon"></i>
                            <i class="devicon-sass-plain colored workHistIcon"></i>
                            <i class="devicon-html5-plain colored workHistIcon"></i>
                            <i class="devicon-bootstrap-plain colored workHistIcon"></i>
                            <i class="devicon-gitlab-plain colored workHistIcon"></i>
                        </div>
                    </WorkDetail>
                </WorkHistory>
                <WorkHistory position="Resident Advisor" company="Eastern Michigan University" location="Ypsilanti, MI" startTime="August 2014" endTime="April 2016">
                    <WorkDetail>
                        Organized/maintained a friendly community in Brown/Munson Apartments. 
                        Assisted residents in various situations. 
                        Planned/Implemented various educational programs. 
                        Demonstrated leadership throughout hall.
                    </WorkDetail>
                    <WorkDetail>
                        Wrote a Google Apps Script Web Application that utilizes Google Forms, 
                        Google Sheets, Google Calendar, and Gmail to organize and assign move 
                        out times for residents throughout the hall.
                        <br />
                        <br />
                        <b><u>Technologies Used</u></b>
                        <br />
                        <div class="icon-container">
                            <i class="devicon-javascript-plain colored workHistIcon"></i>
                            <i class="devicon-google-plain-wordmark colored workHistIcon"></i>
                        </div>
                    </WorkDetail>
                </WorkHistory>
                <WorkHistory position="Software Engineering Intern" company="KLA Laboratories, Inc." location="Dearborn, MI" startTime="July 2015" endTime="August 2015">
                    <WorkDetail>
                        Developed a Visual C# Windows Form Application implementing Microsoft Office 
                        libraries to output a spreadsheet used to complete networking surveys.
                        <br />
                        <br />
                        <b><u>Technologies used for development</u></b>
                        <br />
                        <div class="icon-container">
                            <i class="devicon-csharp-plain colored workHistIcon"></i>
                            <i class="devicon-dot-net-plain colored workHistIcon"></i>
                            <i class="devicon-windows8-plain colored workHistIcon"></i>
                        </div>
                    </WorkDetail>
                </WorkHistory>
            </div>
        </Card>
    </div>
    <div class="col-sm-6 col-xs-12" id="rightCol">
        <Card name="👨‍💻 Skills" desc="I'm a Software Engineer that likes to focus on Mobile &amp; Web Development!" id="#skills">
            <div class="col-xs-12" style="padding: 0px 24px">
                <h4>Platforms</h4>
                <div class="icon-container">
                    <i class="devicon-android-plain colored skillIcon" ></i>
                    <i class="devicon-apple-plain colored skillIcon" data-toggle="tooltip" data-trigger="hover" data-placement="bottom" title="iOS"></i>
                    <i class="devicon-windows8-plain colored skillIcon" data-toggle="tooltip" data-trigger="hover" data-placement="bottom" title="Windows"></i>
                </div>
                <br />
                <h4>Languages</h4>
                <div class="icon-container">
                    <i class="devicon-kotlin-plain-wordmark colored skillIcon"></i>
                    <i class="devicon-java-plain-wordmark colored skillIcon"></i>
                    <i class="devicon-csharp-plain colored skillIcon"></i>
                    <i class="devicon-python-plain-wordmark colored skillIcon"></i>
                    <i class="devicon-c-plain colored skillIcon"></i>
                    <i class="devicon-typescript-plain colored skillIcon"></i>
                    <i class="devicon-javascript-plain colored skillIcon"></i>
                    <i class="devicon-jquery-plain-wordmark colored skillIcon"></i>
                    <i class="devicon-html5-plain-wordmark colored skillIcon"></i>
                    <i class="devicon-css3-plain-wordmark colored skillIcon"></i>
                    <i class="devicon-sass-plain colored skillIcon"></i>
                </div>
                <br />
                <h4>Web Frameworks</h4>
                <div class="icon-container">
                    <i class="devicon-angularjs-plain colored skillIcon"></i>
                    <i class="devicon-react-plain colored skillIcon"></i>
                    <i class="devicon-svelte-plain colored skillIcon"></i>
                    <i class="devicon-bootstrap-plain-wordmark colored skillIcon"></i>
                    <i class="devicon-nodejs-plain colored skillIcon"></i>
                    <i class="devicon-dotnet-plain-wordmark colored skillIcon"></i>
                </div>
                <br />
                <h4>Source Control/Tools</h4>
                <div class="icon-container">
                    <i class="devicon-git-plain-wordmark colored skillIcon"></i>
                    <i class="devicon-github-plain colored skillIcon"></i>
                    <i class="devicon-gitlab-plain colored skillIcon"></i>
                    <i class="devicon-subversion-plain colored skillIcon"></i>
                    <i class="devicon-androidstudio-plain-wordmark skillIcon"></i>
                    <i class="devicon-vscode-plain colored skillIcon"></i>
                </div>
                <br />
                <h4>Testing</h4>
                <div class="icon-container">
                    <i class="devicon-jasmine-plain colored skillIcon"></i>
                    <i class="devicon-android-plain colored skillIcon"></i>
                </div>
                <br />
                <h4>Database</h4>
                <div class="icon-container">
                    <i class="devicon-mysql-plain-wordmark colored skillIcon"></i>
                    <i class="devicon-windows8-plain colored skillIcon" data-toggle="tooltip" data-trigger="hover" data-placement="bottom" title="MSSQL"></i>
                </div>
                <br />
                <br />
                <p>                    
                    I have a lot of experience in programming in Java. It's what EMU used for their curriculum, which helped introduce me to a lot of the core concepts and 
                    ideas of computer science. Learning Java first also helped me learn how to develop Android applications and still helps me today as I write in Kotlin!
                    <br />
                    <br />
                    I've gotten lot of experience with C#, as it is incredibly similar to Java. Developing REST APIs for the products at Daifuku, we ended up using .NET Core,
                    and .NET Standard for some libraries. For my software capstone at EMU, I worked a team of classmates to create a .NET Framework MVC website for a client
                    which interacted with a MySQL database through C#. I also did get some experience using C# with Unity for a game programming class I took. While at KLA,
                    I got an introduction to C# for Windows Forms Apps, and through my time at Daifuku, I've got even more experience with WPF apps. I ended up architecting
                    a handful of MVVM WPF apps which help set up a few JSON files for our web apps, and perform a couple of quality checking processes.
                    <br />
                    <br />
                    Daifuku also introduced me to TypeScript, and I got to architect 2 progressive web apps utilizing Angular. While creating these PWAs, I did a lot of research
                    on web development, modern features of the web, and Angular! I took it upon myself to take what I was working on and make the apps into PWAs, and implemented
                    features that are very beneficial to the products I was developing. This introduced me Service Workers, web app manifests, Web Workers, and other PWA concepts.
                    I started teaching myself JavaScript while still at EMU, and this continued into my position at Daifuku where I work on the entire stack.
                    <br />
                    <br />
                    Rocket HQ helped me further improve my web development skills as I applied what I knew about Angular to their web app, and I also picked up how Jasmine works 
                    for writing unit tests for the web app. When Rocket HQ got aquired by Rocket Homes, this allowed me to move over to the Android team where I got to apply my past 
                    knowledge about Android development and at the same time learn about and implement best practices for Android development. I've learned about various Jetpack
                    components, Google Play APIs, and started writing Kotlin. I'm constantly exploring for new tools I can use for Android development in my job, and continue learning 
                    everyday while I'm there!
                    <br />
                    <br />
                    I think it's an important thing to keep learning whenever you have the opportunity to, and I enjoy learning about different Technologies and how to apply them!
                </p>
            </div>
        </Card>
    </div>
</div>