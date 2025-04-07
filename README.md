# dungeoncrawlhtml
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CLI Dungeon Crawler Report</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            color: #333;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        .section {
            margin-bottom: 30px;
            border-bottom: 1px solid #eee;
            padding-bottom: 20px;
        }
        .command {
            background-color: #f5f5f5;
            padding: 5px 10px;
            border-radius: 4px;
            font-family: monospace;
            display: inline-block;
        }
        .screenshot {
            max-width: 100%;
            height: auto;
            border: 1px solid #ddd;
            margin: 10px 0;
        }
        .path {
            font-family: monospace;
            color: #27ae60;
        }
        .warning {
            background-color: #ffe6e6;
            padding: 10px;
            border-left: 4px solid #e74c3c;
            margin: 10px 0;
        }
        .tip {
            background-color: #e6f7ff;
            padding: 10px;
            border-left: 4px solid #3498db;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>CLI Dungeon Crawler Adventure Report</h1>
        <div class="section">
            <h2>Introduction</h2>
            <p>This report documents my journey through the CLI Dungeon Crawler, a text-based adventure game designed to teach command line interface skills. The objective was to navigate through a simulated directory system to find a hidden reward while learning basic CLI commands.</p>
        </div>
        
        <div class="section">
            <h2>Map of the Dungeon</h2>
            <p>Below is a map of the dungeon structure I discovered:</p>
            <!-- Insert your map image or diagram here -->
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
            <p>Note: Fill in the rest of the map as you discover more areas!</p>
        </div>
        
        <div class="section">
            <h2>Journey Log</h2>
            
            <h3>Starting Point</h3>
            <p>I began at the root directory and used <span class="command">dir</span> to see what was available:</p>
            <p>Found: EntranceGrounds directory, FortressLore.txt, README.md</p>
            <!-- Insert screenshot here -->
            
            <h3>EntranceGrounds</h3>
            <p>Used <span class="command">cd EntranceGrounds</span> to enter the first area.</p>
            <p>Used <span class="command">dir</span> to discover:</p>
            <p>Found: OuterWalls directory, Gatehouse.info</p>
            <!-- Insert screenshot here -->
            
            <h3>OuterWalls</h3>
            <p>Used <span class="command">cd OuterWalls</span> to enter the next area.</p>
            <p>Continue documenting your journey with screenshots...</p>
            
            <!-- Continue adding sections for each area explored -->
        </div>
        
        <div class="section">
            <h2>Challenges Encountered</h2>
            <ul>
                <li>Initial confusion with command syntax (tried using [brackets] in actual commands)</li>
                <li>Learning to navigate between directories using cd ..</li>
                <li>Finding hidden files using dir /a</li>
                <!-- Add more challenges you faced -->
            </ul>
        </div>
        
        <div class="section">
            <h2>CLI Commands Learned</h2>
            <ul>
                <li><span class="command">dir</span> - Lists files and directories</li>
                <li><span class="command">dir /a</span> - Shows hidden files</li>
                <li><span class="command">cd [directory]</span> - Changes to specified directory</li>
                <li><span class="command">cd ..</span> - Moves up one directory level</li>
                <li><span class="command">type [file]</span> - Displays contents of a text file</li>
                <li><span class="command">findstr [pattern] [file]</span> - Searches for text in files</li>
                <!-- Add more commands as you use them -->
            </ul>
        </div>
        
        <div class="section">
            <h2>The Final Reward</h2>
            <p>After navigating through the dungeon, I really wanted to find the reward but unfortunately i could not be able to do it. but im sure that i can say i learnt many functions and commands...</p>
            <!-- Describe what you found and where -->
            <!-- Insert screenshot of the final reward -->
        </div>
        
        <div class="section">
            <h2>Conclusion</h2>
            <p>This CLI Dungeon Crawler adventure taught me valuable skills in command line navigation and file manipulation. I learned how to use basic commands to explore directory structures, read files, search for specific text, and understand file hierarchies.</p>
            <p>These skills will be useful for future programming tasks and understanding how computers organize data.</p>
        </div>
    </div>
</body>
</html>
