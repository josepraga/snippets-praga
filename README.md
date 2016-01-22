# snippets-praga
Snippets 

Run Rspec
    
    bundle exec rspec
    
Codacy Gem

    gem 'codacy-coverage', :require => false

Bootstrap slider

    <div class="slider slider-horizontal" style="width: 414px;"><div class="slider-track"><div class="slider-selection" style="left: 16.1616%; width: 17.1717%;"></div><div class="slider-handle round" style="left: 16.1616%;"></div><div class="slider-handle round" style="left: 33.3333%;"></div></div><div class="tooltip top in" style="top: -40px; left: 68.4545px;"><div class="tooltip-arrow"></div><div class="tooltip-inner">170 : 1000</div></div><input type="text" class="span2" value="" data-slider-min="10" data-slider-max="1000" data-slider-step="5" data-slider-value="[250,450]" id="sl2"></div>

Jquery UI

    $(function() {
        $( "#slider-range" ).slider({
            range: true,
            min: 0,
            max: 500,
            values: [ 75, 300 ],
            slide: function( event, ui ) {
                $( "#amount" ).val( "$" + ui.values[ 0 ] + " - $" + ui.values[ 1 ] );
            }
        });
        $( "#amount" ).val( "$" + $( "#slider-range" ).slider( "values", 0 ) +
            " - $" + $( "#slider-range" ).slider( "values", 1 ) );
    });
    
    // for the template
    <div id="slider-range"></div>

