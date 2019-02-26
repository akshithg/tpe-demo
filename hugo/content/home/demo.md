---
title: "Demo"
weight: 4
---

<script src="tpe.js"></script>
<link href="tpe.css" type="text/css" rel="stylesheet" />

<div id="ddemo" class="box-col">
<section>
    <!-- Select image -->
    <div><input type="file" name="Browse" id="browse" accept="image/*" class="action-button"></div>
    <span>
    <div>Number of iterations:<input type="number" name="iterations" id="iterations" min="1" required> </div>
    <div>&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;Block Size:<input type="number" name="blocksize" id="blocksize" min="1" required> </div>
    <div id="abc">&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;Key:&#160;&#160;&#160;&#160;<input type="text" name="key" id="key" required> </div>
    <div><button id="set" class="button">Set</button></div>
    </span>
    <!-- Original image -->
    <div class="box-row">
        <!-- image -->
        <div class="canvas-container">
            <div> Original Image </div>
            <canvas class="canvas-image" id="canvas-og"></canvas>
        </div>
        <!-- thumbnail -->
        <div class="canvas-container">
            <div> Original Image Thumbnail </div>
            <canvas class="canvas-image-thumbnail" id="canvas-ogt"></canvas>
        </div>
    </div>
    <!-- Encrypt image -->
    <div><button id="encrypt" class="button">Encrypt</button></div>
    <div class="box-row">
        <!-- image -->
        <div class="canvas-container">
            <div> Encrypted Image </div>
            <canvas class="canvas-image" id="canvas-en"></canvas>
        </div>
        <!-- thumbnail -->
        <div class="canvas-container">
            <div> Encrypted Image Thumbnail </div>
            <canvas class="canvas-image-thumbnail" id="canvas-ent"></canvas>
        </div>
    </div>
    <!-- Decrypted image -->
    <div><button id="decrypt" class="button">Decrypt</button></div>
    <div class="box-row">
        <!-- image -->
        <div class="canvas-container">
            <div> Decrypted Image</div>
            <canvas class="canvas-image" id="canvas-de"></canvas>
        </div>
        <!-- thumbnail -->
        <div class="canvas-container">
            <div> Decrypted Image Thumbnail</div>
            <canvas class="canvas-image-thumbnail" id="canvas-det"></canvas>
        </div>
    </div>
</section>
</div>
