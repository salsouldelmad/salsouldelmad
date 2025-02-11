---
layout: default
title: Welcome to My Site
---

# Welcome to Our Page!

## About SalSoul Del Mad
Salsa and Soul, we combine the best of two cultural worlds bringing together the fire of latin rhythm and the groove of soul. Orquesta Salsoul Del Mad will have young and old dancing in the aisle and on the ceiling. Voted best latin performer of the year by MAMA (Madison Area Music Award) as well as the 2022 WAMI (Wisconsin Area Music Industry) award nominee.

This Orquesta is made up of some of the best local musicians representing the international diversity of Madison. They were first introduced to the public at the 2015 Latino Musical Festival, and are looking to book other venues appropriate for a 15 piece group.

## Section 2: Video Content
<div class="youtube-container">
    <!-- Clickable thumbnail with YouTube play button overlay -->
    <a id="youtube-thumbnail" href="https://www.youtube.com/watch?v=fBW_GfMCTFY" target="_blank">
        <div class="thumbnail-wrapper">
            <img id="youtube-thumb-img" src="https://img.youtube.com/vi/fBW_GfMCTFY/maxresdefault.jpg" 
                alt="YouTube Thumbnail" onerror="this.src='https://img.youtube.com/vi/fBW_GfMCTFY/hqdefault.jpg'">
            <div class="youtube-overlay">
                <div class="youtube-play-icon"></div>
            </div>
        </div>
    </a>

    <!-- The actual embedded YouTube video -->
    <iframe id="youtube-video" width="560" height="315" 
        src="https://www.youtube-nocookie.com/embed/fBW_GfMCTFY" 
        frameborder="0" allowfullscreen>
    </iframe>
</div>

<script>
    document.addEventListener("DOMContentLoaded", function () {
        let iframe = document.getElementById("youtube-video");
        let thumbnail = document.getElementById("youtube-thumbnail");

        // Check if the video loads
        setTimeout(() => {
            if (!iframe.contentWindow || iframe.contentWindow.length === 0) {
                console.log("Video unavailable, showing thumbnail.");
                iframe.style.display = "none";
                thumbnail.style.display = "block";
            } else {
                thumbnail.style.display = "none"; // Hide thumbnail if video loads
            }
        }, 1000); // Wait 1 second to detect failure
    });
</script>

<style>
    .youtube-container {
        text-align: center;
        position: relative;
    }

    .thumbnail-wrapper {
        position: relative;
        display: inline-block;
        cursor: pointer;
    }

    #youtube-thumbnail {
        display: none;
        text-decoration: none;
    }

    #youtube-thumb-img {
        width: 560px;
        height: 315px;
        border-radius: 8px;
    }

    /* YouTube-style play button overlay */
    .youtube-overlay {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 90px;
        height: 64px;
        background: rgba(0, 0, 0, 0.6);
        border-radius: 12px;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .youtube-play-icon {
        width: 0;
        height: 0;
        border-left: 40px solid white;
        border-top: 25px solid transparent;
        border-bottom: 25px solid transparent;
        margin-left: 5px;
    }

    /* Hover effect */
    .youtube-overlay:hover {
        background: rgba(0, 0, 0, 0.8);
    }
</style>

## Section 3: Music
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/868642210&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/alise-mosley" title="Alise Mosley" target="_blank" style="color: #cccccc; text-decoration: none;">Alise Mosley</a> · <a href="https://soundcloud.com/alise-mosley/intertwined" title="Intertwined" target="_blank" style="color: #cccccc; text-decoration: none;">Intertwined</a></div>