# Material Expansion Panels

**Material Expansion Panel** is a plugin that allows you to expand the panel
content when clicked on the panel. The panel content collapses on clicking again 
on the panel.The **material expansion panel** is created following [Material design guidelines](https://material.io/guidelines/components/buttons.html#) and the 
classes are named following the naming convention of [BEM methodology](https://en.bem.info/methodology/naming-convention/).
              

The classes used for creating the panel along with a toggle button and the panel content is mentioned below. If clicked on the toggle
button, the content of the panel expands and collapses:
   

      <div class="md-expansion-panel">
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
          
          <div class="zippy" id="expand-1">
              <div class="md-expansion-panel__wrapper zippy__wrapper">
                    <div class="md-expansion-panel__body">
                        <p>
                         Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                         Ex fugiat in modi obcaecati odio praesentium ratione similique 
                         sint velit voluptatem! Alias aliquam amet enim facere fugiat
                        </p>
                    </div>
              </div>
          </div>
      </div>

## Demo

 <a href="https://codeartisan-ui.github.io/material-expansion-panels/" target="_blank">Material Expansion Panels</a>



