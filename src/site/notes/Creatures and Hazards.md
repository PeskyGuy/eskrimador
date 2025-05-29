---
{"dg-publish":true,"permalink":"/creatures-and-hazards/"}
---

<style>
.hazard-statblock {
    font-family: 'Noto Serif JP', serif;
    background: #f9f5f0;
    border: 2px solid #2c1810;
    border-radius: 8px;
    padding: 20px;
    margin: 20px 0;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    position: relative;
}

.hazard-statblock::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><path d="M0,0 L100,100 M100,0 L0,100" stroke="%232c1810" stroke-width="0.5" opacity="0.1"/></svg>');
    pointer-events: none;
    border-radius: 6px;
}

.hazard-header {
    border-bottom: 2px solid #2c1810;
    margin-bottom: 15px;
    padding-bottom: 10px;
}

.hazard-name {
    font-size: 24px;
    font-weight: bold;
    color: #2c1810;
    margin: 0;
    text-transform: uppercase;
    letter-spacing: 1px;
}

.hazard-level {
    font-size: 18px;
    color: #5c3d2e;
    margin: 5px 0;
    font-style: italic;
}

.hazard-description {
    background: #fff;
    border: 1px solid #2c1810;
    padding: 15px;
    margin: 15px 0;
    border-radius: 4px;
    min-height: 100px;
}

.hazard-actions {
    margin-top: 20px;
}

.hazard-action {
    border-left: 3px solid #2c1810;
    padding-left: 15px;
    margin: 10px 0;
}

.hazard-trait {
    font-style: italic;
    color: #5c3d2e;
    margin: 5px 0;
}

/* Ink splatter decorative elements */
.hazard-statblock::after {
    content: '';
    position: absolute;
    top: -10px;
    right: -10px;
    width: 100px;
    height: 100px;
    background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><path d="M50,0 Q80,20 90,50 Q100,80 70,90 Q40,100 20,80 Q0,60 10,30 Q20,0 50,0" fill="%232c1810" opacity="0.05"/></svg>');
    pointer-events: none;
    z-index: -1;
}
</style>

<div class="hazard-statblock">
    <div class="hazard-header">
        <h2 class="hazard-name">HAZARD: [Name]</h2>
        <div class="hazard-level">HAZARD LEVEL: [Number]</div>
    </div>
    
    <div class="hazard-description">
        [Description goes here]
    </div>
    
    <div class="hazard-actions">
        <h3>Actions & Traits</h3>
        <div class="hazard-action">
            <strong>[Action Name]</strong>
            <div class="hazard-trait">[Action Description]</div>
        </div>
        <!-- Additional actions can be added here -->
    </div>
</div>
