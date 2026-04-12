<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <style>
        @page {
            size: A4;
            margin: 20mm;
            background-color: #ffffff;
        }
        body {
            font-family: 'Times New Roman', serif;
            color: #333;
            line-height: 1.6;
            font-size: 11pt;
            margin: 0;
            padding: 0;
        }
        .banner {
            background-color: #1a535c;
            color: #d4c8aa;
            padding: 20px;
            text-align: center;
            border-radius: 4px;
            margin-bottom: 30px;
        }
        .banner h1 {
            margin: 0;
            font-size: 24pt;
            letter-spacing: 2px;
        }
        .banner p {
            margin: 5px 0 0 0;
            font-style: italic;
            font-size: 12pt;
        }
        .disclaimer {
            border: 2px solid #e74c3c;
            background-color: #fdf2f2;
            padding: 15px;
            margin-bottom: 30px;
            font-weight: bold;
            color: #800000;
        }
        h2 {
            color: #1a535c;
            border-left: 5px solid #3498db;
            padding-left: 10px;
            margin-top: 25px;
            font-size: 16pt;
        }
        h3 {
            color: #1a535c;
            font-size: 13pt;
            margin-top: 20px;
            border-bottom: 1px solid #ddd;
        }
        ul, ol {
            margin-bottom: 15px;
        }
        li {
            margin-bottom: 8px;
        }
        .key-box {
            background-color: #f8f9fa;
            border: 1px solid #ccc;
            padding: 10px;
            font-family: 'Courier New', monospace;
            display: inline-block;
            margin: 2px;
            border-radius: 3px;
            font-size: 10pt;
        }
        .callout {
            background-color: #fdfdf5;
            border-left: 4px solid #d4c8aa;
            padding: 10px 15px;
            margin: 15px 0;
            font-style: italic;
        }
        .important {
            color: #800000;
            font-weight: bold;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="banner">
        <h1>SYNTAXIS</h1>
        <p>The Exegetical Toolkit v11.2</p>
    </div>

    <div class="disclaimer">
        DISCLAIMER: I am not the author of this code. This application was conceptualized by me and developed through a collaborative process using Artificial Intelligence. I provide this tool for educational and analytical purposes with full transparency regarding its origin.
    </div>

    <h2>Overview</h2>
    <p>Syntaxis is a specialized software environment designed for the precision diagramming of complex textual structures. This version (v11.2) is optimized for handling larger blocks of text with high-stability tools for morphological analysis and notation.</p>

    <h2>Getting Started</h2>
    <ol>
        <li><strong>Load Your Text:</strong> Enter your scripture reference and passage in the top panel. Click <strong>Update</strong> to populate the Word Bank.</li>
        <li><strong>Managing Large Passages:</strong> For longer passages (e.g., Colossians 1:1-8), the Word Bank is now <span class="important">scrollable</span>. This allows you to browse all available words without the interface pushing your canvas down.</li>
        <li><strong>Deploy Words:</strong> Click any word in the bank to place it on the canvas.</li>
    </ol>

    <h2>Core Functions & Controls</h2>

    <h3>1. Lexicon Integration (Blue Letter Bible)</h3>
    <p>Syntaxis can automatically link words to their morphological entries. Hold <span class="key-box">Option</span> and <strong>Click</strong> on a word to open its entry in a new tab.</p>
    <div class="callout">
        <span class="important">CRITICAL CAVEAT:</span> For the link system to work, you must use proper capitalization in the reference box. For example, use <strong>"Colossians"</strong> or <strong>"John"</strong> instead of "colossians" or "john." Lowercase book names will cause the link system to fail.
    </div>

    <h3>2. Notation & Footnotes</h3>
    <p>Hold <span class="key-box">Option</span> + <span class="key-box">Cmd/Ctrl</span> and <strong>Click</strong> on a word to add a footnote.
    <ul>
        <li>A red dot will appear above the word.</li>
        <li>The word is now "locked" to its note; moving the word will move the red dot with it.</li>
        <li>Click the red dot at any time to edit your analysis.</li>
    </ul></p>

    <h3>3. The Universal Curve</h3>
    <p>Use the curve tool for non-linear syntactical relationships. 
    <ul>
        <li>Drag the <strong>Dark Teal Dots</strong> to set your start and end points.</li>
        <li>Drag the <strong>Light Blue Dot</strong> to adjust the arc.</li>
        <li>Deleting the curve now automatically removes its handles for a clean workspace.</li>
    </ul></p>

    <h2>Keyboard Shortcuts</h2>
    <ul>
        <li><strong>Fine-Tune Position:</strong> Select an object and use <span class="key-box">&uarr; &darr; &larr; &rarr;</span> to move 1px.</li>
        <li><strong>Fast Jump:</strong> Hold <span class="key-box">Shift</span> + <span class="key-box">Arrow Keys</span> to move 10px.</li>
        <li><strong>Deletion:</strong> Hit <span class="key-box">Backspace</span> or <span class="key-box">Delete</span> to remove selected items.</li>
    </ul>

    <h2>Project Management</h2>
    <p>Use the <strong>Save As...</strong> button to save your work as a .json file. To resume a project, simply refresh the program and load your saved data using your browser's local file management.</p>
</body>
