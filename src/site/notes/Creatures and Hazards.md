---
{"dg-publish":true,"permalink":"/creatures-and-hazards/"}
---

<div style="border: 2px solid #2c1810; border-radius: 8px; padding: 20px; background-color: #f9f5f0; margin: 20px 0;">
    <!-- Header Section -->
    <div style="border-bottom: 2px solid #2c1810; margin-bottom: 15px; padding-bottom: 10px;">
        <input type="text" id="hazardName" value="[Name]" style="width: 100%; margin: 0; color: #2c1810; font-size: 24px; text-transform: uppercase; letter-spacing: 1px; border: none; background: transparent; font-weight: bold; font-family: inherit;" placeholder="Enter Hazard Name">
        <div style="color: #5c3d2e; font-size: 18px; font-style: italic; margin-top: 5px;">
            <input type="number" id="hazardLevel" value="[Number]" style="width: 60px; border: 1px solid #5c3d2e; border-radius: 4px; padding: 2px 5px; background: white;" min="1" max="10"> HAZARD LEVEL
        </div>
    </div>
    
    <!-- Description Section -->
    <div style="background: white; border: 1px solid #2c1810; padding: 15px; margin: 15px 0; border-radius: 4px; min-height: 100px;">
        <textarea id="hazardDescription" style="width: 100%; min-height: 100px; border: none; resize: vertical; color: #1a0f0a; font-family: inherit;" placeholder="Enter hazard description here">[Description goes here]</textarea>
    </div>
    
    <!-- Actions & Traits Section -->
    <div style="margin-top: 20px;">
        <h3 style="margin: 0 0 15px 0; color: #2c1810;">Actions & Traits</h3>
        
        <!-- Action Example -->
        <div style="border-left: 3px solid #2c1810; padding-left: 15px; margin: 10px 0;">
            <input type="text" class="action-name" value="[Action Name]" style="width: 100%; border: none; background: transparent; color: #2c1810; font-weight: bold; font-family: inherit;" placeholder="Enter Action Name">
            <textarea class="action-description" style="width: 100%; border: none; background: transparent; color: #5c3d2e; font-style: italic; margin-top: 5px; resize: vertical; min-height: 40px; font-family: inherit;" placeholder="Enter action description">[Action Description]</textarea>
        </div>
    </div>
</div>
