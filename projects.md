---
layout: page
title: Projects
description: My Portfolio
image: assets/images/projects.jpg
nav-menu: true
---

<div class="inner" style="max-width: 800px; margin: 0 auto; padding: 2em 40px; background-color: rgba(255, 255, 255, 0.0); border-radius: 5px;">
    <section>
        <div class="content">
            <h2 style="text-align: center;">Featured Projects</h2>

            <div class="box">
                <h3>Study Buddy</h3>
                <p>Built an end-to-end Android application allowing USC students to form study groups, exchange resources
                in private/group chats, and schedule sessions via Google Calendar’s API. Developed a Firebase backend
                (Realtime Database, Storage, Authentication) for real-time collaboration and secure user management.</p>
                <ul class="actions">
                    <li><a href="#" class="button fix-links-btn">View Project</a></li>
                </ul>
            </div>

            <div class="box">
                <h3>POS Tagger</h3>
                <p>Implemented a Hidden Markov Model with the Viterbi algorithm to perform part-of-speech tagging on large text corpora. Achieved highly accurate predictions by refining transmission and emission probabilities with iterative training.</p>
                <ul class="actions">
                    <li><a href="#" class="button fix-links-btn">View Project</a></li>
                </ul>
            </div>
            
            <div class="box">
                <h3>LIGO Data Quality Classification</h3>
                <p>Developed a neural network to characterize gravitational wave detector data quality in real-time for analysis of black hole collision physics.</p>
                <ul class="actions">
                    <li><a href="#" class="button fix-links-btn">View Project</a></li>
                </ul>
            </div>

            <div class="box">
                <h3>Portal Video Game</h3>
                <p>Developed a 3D puzzle game from scratch entirely in C using SDL2. Implemented real-time rendering, custom view matrices for portal views, and a multichannel audio system. Utilized linear algebra techniques to handle dynamic camera perspectives and seamless perspective shifts.</p>
                <ul class="actions">
                    <li><a href="#" class="button fix-links-btn">View Project</a></li>
                </ul>
            </div>

            <div class="box">
                <h3>Personal Website</h3>
                <p>Designed and developed a responsive personal website using Jekyll and GitHub Pages. Implemented custom styling and content management system.</p>
                <ul class="actions">
                    <li><a href="#" class="button fix-links-btn">View Project</a></li>
                </ul>
            </div>
            
        </div>
    </section>
</div>

<script>
    document.querySelectorAll('.fix-links-btn').forEach(button => {
        button.addEventListener('click', function(event) {
            event.preventDefault(); 
            alert('Links being fixed');
        });
    });
</script>
