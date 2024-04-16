<script>
    let firstSentance = ""
    let secondSentance = ""
    let thirdSentance = ""
    let fourthSentance = ""
    let fifthSentance = ""
    function about(){
        firstSentance = "Hello, Welcome To Zivgates";
        secondSentance = "This is the homepage, As I'm Planning to add more pages to the website in the future.";
        thirdSentance = "This is the direct replacement to zvqle's realm, so this will be my main focus from now on.";
        fourthSentance = "I have large plans for this website, so make sure to follow my github to see more!"
        fifthSentance = "";

    }
    function clear(){
        firstSentance = "";
        secondSentance = "";
        thirdSentance = "";
        fourthSentance = "";
        fifthSentance = "";

    }
    function aboutMe(){
        firstSentance = "Hello, I'm zvqle (not revealing my real name 😉).";
        secondSentance = "I'm Mainly a C/C++ and F# Programmer, But I also enjoy making Web Apps.";
        thirdSentance = "I also enjoy talking geopolitics, maps, and making flags";
        fourthSentance = "Visit My Twitter, Github, And Youtube To see What I Make.";
        fifthSentance = "🇸🇴/🇺🇸";
    }
    function myProjects(){
        firstSentance = "Layl-Shell<br><br>A Command-Line for Windows<br><br><a href=\"https://github.com/realzvqle/layl-shell\">Link</a>";
        secondSentance = "Trojen.Win32.Vuvuria<br><br>A Malware written for educational purposes<br><br><a href=\"https://github.com/realzvqle/codename-quantalysm\">Link</a>";
        thirdSentance = "Skid-Engine<br><br>A Malware Maker for all the skids<br><br><a href=\"https://github.com/zivgates/Skid-Engine\">Link</a>";
        fourthSentance = "";
        fifthSentance = "";
    }
</script>


<body>
    <div class="container">
        <div class="anothercontainter">
            <embed src="../favicon.png" width="70" height="70">
            <h1>ZivGates</h1>
            <h6>zvqles personal site</h6>
            <br>
            <h5>{@html firstSentance}</h5>
            <h5>{@html secondSentance}</h5>
            <h5>{@html thirdSentance}</h5>
            <h5>{@html fourthSentance}</h5>
            <h5>{@html fifthSentance}</h5>
            <button on:click={about}>About</button>
            <br>
            <br>
            <button on:click={aboutMe}>About Me</button>
            <button on:click={myProjects}>My Projects</button>
            <br>
            <br>
            <button on:click={clear}>Clear</button>


        </div>
        
    </div>
    <footer>
        <br>
        <a href="https://twitter.com/realzvqle">twitter</a>
        <a href="https://youtube.com/zvqle">⠀⠀⠀⠀youtube</a>
        <a href="https://github.com/realzvqle">⠀⠀⠀⠀github</a>
        <br>
        <h6>Copyright "zvqle", all rights reserved</h6>
    </footer>
</body>
