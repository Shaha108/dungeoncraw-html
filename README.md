<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CLI Dungeon Crawler Adventure</title>
    <style>
        body {
            font-family: 'Verdana', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #2e4053;
        }
        .container {
            max-width: 850px;
            margin: 0 auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section {
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 1px solid #ddd;
        }
        .command {
            background: #e8f6f3;
            padding: 5px 10px;
            border-radius: 5px;
            font-family: monospace;
            display: inline-block;
        }
        .screenshot {
            max-width: 100%;
            height: auto;
            border: 1px solid #bbb;
            margin: 10px 0;
        }
        .path {
            font-family: monospace;
            color: #229954;
        }
        .note {
            background: #fcf3cf;
            padding: 10px;
            border-left: 5px solid #f1c40f;
            margin: 10px 0;
        }
        .alert {
            background: #f8d7da;
            padding: 10px;
            border-left: 5px solid #c0392b;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>CLI Dungeon Crawler Adventure</h1>
        
        <div class="section">
            <h2>Introduction</h2>
            <p>This report documents my journey through the CLI Dungeon Crawler, a text-based game designed to enhance my command-line skills. The goal was to navigate through a simulated file system, uncovering hidden files and directories while learning essential CLI commands.</p>
        </div>
        
        <div class="section">
            <h2>Dungeon Map</h2>
            <p>The following is a representation of the directory structure I encountered during my journey:</p>
            <pre>
Root (C:\)
├── EntranceGrounds/
│   ├── FortressLore.txt
│   ├── README.md
│   ├── Gatehouse.info
│   └── OuterWalls/
│       └── InnerKeep/
│           ├── GreatHall.info
│           ├── OldRecords.tome
│           └── Armory/
│               └── Weapon.box and StoneKey.key
            </pre>
            <p class="note">Note: More areas might exist beyond what I discovered.</p>
        </div>
        
        <div class="section">
            <h2>Exploration Log</h2>
            
            <h3>Starting Point</h3>
            <p>At the root directory, I used <span class="command">dir</span> to check the available files and folders:</p>
            <p>Discovered: EntranceGrounds directory, FortressLore.txt, README.md</p>
            
            <h3>Entering the EntranceGrounds</h3>
            <p>Executed <span class="command">cd EntranceGrounds</span> to move forward.</p>
            <p>Checked contents using <span class="command">dir</span> and found:</p>
            <p>New discoveries: OuterWalls directory, Gatehouse.info</p>
            
            <h3>Venturing into OuterWalls</h3>
            <p>Used <span class="command">cd OuterWalls</span> to go further.</p>
            <p>Inside, I found additional directories leading deeper into the dungeon.</p>
        </div>
        
        <div class="section">
            <h2>Challenges Encountered</h2>
            <ul>
                <li>Had trouble at first with command syntax (e.g., mistakenly using brackets in commands).</li>
                <li>Took time to understand <span class="command">cd ..</span> for moving back to previous directories.</li>
                <li>Learned how to display hidden files using <span class="command">dir /a</span>.</li>
            </ul>
        </div>
        
        <div class="section">
            <h2>Important CLI Commands Learned</h2>
            <ul>
                <li><span class="command">dir</span> - Lists files and directories.</li>
                <li><span class="command">dir /a</span> - Displays hidden files.</li>
                <li><span class="command">cd [directory]</span> - Moves into a specified directory.</li>
                <li><span class="command">cd ..</span> - Moves back to the previous directory.</li>
                <li><span class="command">type [file]</span> - Shows the content of a text file.</li>
                <li><span class="command">findstr [word] [file]</span> - Searches for a specific word in a file.</li>
            </ul>
        </div>
        
        <div class="section">
            <h2>The Final Reward</h2>
            <p>Despite exploring various directories, I was unable to locate the ultimate treasure. However, the journey itself was rewarding as I gained valuable experience in using command-line tools.</p>
        </div>
        
        <div class="section">
            <h2>Conclusion</h2>
            <p>This adventure provided an excellent way to practice command-line navigation and file management. The skills I acquired will be useful for future projects involving system operations and file handling.</p>
        </div>
    </div>
</body>
</html>
