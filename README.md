# Material Expansion Panels

**Material Expansion Panel** is a plugin that allows you to expand the panel
content when clicked on the panel. The panel content collapses on clicking again 
on the panel.

The classes used for creating the panel along with a toggle button. If clicked on the toggle
button, the content of the panel expands:
   

      <div class="md-expansion-panel__header">
            <div class="md-expansion-panel__header-body">
                    Click to Expand the Content
             </div>
            <div class="md-expansion-panel__header-button">
                    <button class="md-button md-button--icon" id="toggle-button" data-toggle="zippy" data-target="#expand-1">
                    <i class="material-icons">expand_more</i>
                    </button>
            </div>
    </div>

The classes used for panel content is:

        <div class="zippy" id="expand-1">
            <div class="md-expansion-panel__wrapper zippy__wrapper">
                <div class="md-expansion-panel__body">
                        <p> Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                            similique sint velit voluptatem! Alias aliquam amet enim 
                        </p>
                </div>
            </div>
        </div>
        
## Demo

 <a href="https://codeartisan-ui.github.io/material-expansion-panels/" target="_blank">Material Expansion Panels</a>



