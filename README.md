<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wicked Engine</title>
</head>
<body>
    <img align="left" src="Content/logo_small.png" width="180px"/>

    <h1>Wicked Engine</h1>

    <p>
        <a href="https://github.com/turanszkij/WickedEngine/actions">
            <img src="https://github.com/turanszkij/WickedEngine/workflows/Build/badge.svg" alt="Github Build Status"/>
        </a>
        <a href="https://discord.gg/CFjRYmE">
            <img src="https://img.shields.io/discord/602811659224088577?logo=discord" alt="Discord chat"/>
        </a>
        <a href="https://wickedengine.net/forum/">
            <img src="https://img.shields.io/badge/forum-join-blue" alt="Forum"/>
        </a>
        <a href="https://twitter.com/intent/follow?screen_name=turanszkij">
            <img src="https://img.shields.io/twitter/follow/turanszkij.svg?style=social" alt="follow on Twitter"/>
        </a>
        <br/>
        <a href="https://store.steampowered.com/app/1967460/Wicked_Engine/">
            <img src="https://img.shields.io/badge/-Steam-383838.svg?style=for-the-badge&logo=steam" alt="Steam"/>
        </a>
    </p>

    <br/>

    <img align="right" src="https://github.com/turanszkij/wickedengine-gifs/raw/main/videoprojectors.gif" width="320px"/>
    <p>
        Wicked Engine is an open-source 3D engine with modern graphics. Use this as a C++ framework for your graphics projects, a standalone 3D editor, LUA scripting or just for learning.
    </p>
    <ul>
        <li><a href="https://wickedengine.net/">Website</a></li>
        <li><a href="https://wickedengine.net/forum/">Forum</a></li>
        <li><a href="features.txt">Features</a></li>
        <li><a href="https://www.youtube.com/playlist?list=PLLN-1FTGyLU_HJoC5zx6hJkB3D2XLiaxS">Videos</a></li>
        <li><a href="Content/Documentation/WickedEngine-Documentation.md">C++ Documentation</a></li>
        <li><a href="Content/Documentation/ScriptingAPI-Documentation.md">Lua Documentation</a></li>
    </ul>

    <p>
        You can get the full source code by using Git version control and cloning <a href="https://github.com/turanszkij/WickedEngine.git">https://github.com/turanszkij/WickedEngine.git</a>, or downloading it as zip. You can also download nightly packaged builds of the Editor here (requires Github sign in):
        <a href="https://github.com/turanszkij/WickedEngine/actions">
            <img src="https://github.com/turanszkij/WickedEngine/workflows/Build/badge.svg" alt="Github Build Status"/>
        </a>
    </p>

    <br/>
    <br/>

    <img align="right" src="https://github.com/turanszkij/wickedengine-gifs/raw/main/swimming.gif" width="320px"/>

    <h2>Platforms:</h2>
    <ul>
        <li>Windows 10 or newer</li>
        <li>Linux</li>
        <li>Xbox Series X|S</li>
        <li>PlayStation 5</li>
    </ul>

    <h2>How to build:</h2>

    <h3>Windows</h3>
    <p>
        To build Wicked Engine for Windows (10 or later), use the latest version of Visual Studio and the provided <code>WickedEngine.sln</code> solution file. By simply pressing F5, the Editor application will be built. There are other example projects that you can build as well within the solution.
    </p>

    <img align="right" src="https://github.com/turanszkij/wickedengine-gifs/raw/main/fighting_game.gif" width="320px"/>

    <p>
        If you want to develop a C++ application that uses Wicked Engine, you can build the WickedEngine static library project for the appropriate platform, such as <code>WickedEngine_Windows</code> and link against it. Including the <code>"WickedEngine.h"</code> header will attempt to link the binaries for the appropriate platform, but search directories should be set up beforehand. For example, you can set additional library directories to <code>$(SolutionDir)BUILD\$(Platform)\$(Configuration)</code> by default. For examples, see the <code>Template</code>, <code>Tests</code>, and <code>Editor</code> projects.
    </p>

    <p>
        If you have questions or stuck, please use the <code>windows</code> communication channel on Discord:
        <a href="https://discord.gg/CFjRYmE">
            <img src="https://img.shields.io/discord/602811659224088577?logo=discord" alt="Discord chat"/>
        </a>
    </p>

    <img align="right" src="https://github.com
