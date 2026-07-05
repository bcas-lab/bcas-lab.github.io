---
title: Gallery
date: 2026-07-01
type: landing

sections:
  - block: markdown
    content:
      title: Gallery
      subtitle: Lab activities, conferences, events, and IC/system prototypes
      text: |
        <div class="gallery-category-grid">

          <a class="gallery-category-card" href="./lab-life/">
            <img src="/media/gallery/lab-life/cover.jpg" alt="Lab Life">
            <div class="gallery-category-card-body">
              <h3>Lab Life</h3>
              <p>Photos from BCAS Lab activities, milestones, and daily research life.</p>
            </div>
          </a>

          <a class="gallery-category-card" href="./conferences-events/">
            <img src="/media/gallery/conferences-events/cover.jpg" alt="Conferences and Events">
            <div class="gallery-category-card-body">
              <h3>Conferences & Events</h3>
              <p>Conference participation, awards, invited talks, and academic events.</p>
            </div>
          </a>

          <a class="gallery-category-card" href="./ic-system-prototypes/">
            <img src="/media/gallery/ic-system-prototypes/cover.jpg" alt="IC and System Prototypes">
            <div class="gallery-category-card-body">
              <h3>IC & System Prototypes</h3>
              <p>Integrated circuits, PCBs, wireless systems, and biomedical prototypes.</p>
            </div>
          </a>

        </div>

        <style>
          .gallery-category-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 24px;
            margin-top: 30px;
          }

          .gallery-category-card {
            display: block;
            text-decoration: none;
            color: inherit;
            border-radius: 14px;
            overflow: hidden;
            background: #fff;
            box-shadow: 0 4px 18px rgba(0,0,0,0.10);
            transition: transform 0.2s ease, box-shadow 0.2s ease;
          }

          .gallery-category-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 8px 24px rgba(0,0,0,0.16);
            text-decoration: none;
          }

          .gallery-category-card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            display: block;
          }

          .gallery-category-card-body {
            padding: 18px 20px 20px 20px;
          }

          .gallery-category-card-body h3 {
            margin-top: 0;
            margin-bottom: 8px;
          }

          .gallery-category-card-body p {
            margin-bottom: 0;
            color: #555;
            font-size: 0.95rem;
          }
        </style>
    design:
      columns: '1'
---