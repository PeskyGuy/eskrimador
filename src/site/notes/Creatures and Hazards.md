---
{"dg-publish":true,"permalink":"/creatures-and-hazards/"}
---

<style>
.hazard-statblock {
    --callout-color: 44, 24, 16;
    --callout-icon: sword;
    --callout-title-color: rgb(44, 24, 16);
    --callout-content-background: #f9f5f0;
    --callout-border-width: 2px;
    --callout-border-opacity: 0.8;
    --callout-radius: 8px;
    font-family: 'Noto Serif JP', serif;
}

.hazard-statblock .callout-content {
    position: relative;
}

.hazard-statblock .callout-content::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><path d="M0,0 L100,100 M100,0 L0,100" stroke="%232c1810" stroke-width="0.5" opacity="0.1"/></svg>');
    pointer-events: none;
    border-radius: 6px;
    z-index: 0;
}

.hazard-statblock .hazard-name {
    font-size: 1.5em;
    font-weight: bold;
    color: var(--callout-title-color);
    margin: 0;
    text-transform: uppercase;
    letter-spacing: 1px;
    border-bottom: 2px solid rgba(var(--callout-color), 0.8);
    padding-bottom: 0.5em;
    margin-bottom: 0.5em;
}

.hazard-statblock .hazard-level {
    font-size: 1.2em;
    color: rgb(92, 61, 46);
    margin: 0.5em 0;
    font-style: italic;
}

.hazard-statblock .hazard-description {
    background: #fff;
    border: 1px solid rgba(var(--callout-color), 0.8);
    padding: 1em;
    margin: 1em 0;
    border-radius: 4px;
    min-height: 100px;
}

.hazard-statblock .hazard-actions {
    margin-top: 1.5em;
}

.hazard-statblock .hazard-action {
    border-left: 3px solid rgba(var(--callout-color), 0.8);
    padding-left: 1em;
    margin: 0.8em 0;
}

.hazard-statblock .hazard-trait {
    font-style: italic;
    color: rgb(92, 61, 46);
    margin: 0.3em 0;
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
    </div>
</div>
