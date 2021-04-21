# OnlyBgSlider
A simple slider that only changes the background image of the block without changing its content
Step 1 paste cloning directory in your project

Step 2 include script <code>OnlyBgSLider.min.js</code>


<code> < script src="{path_to_directory}/OnlyBgSlider/OnlyBgSlider.min.js"></> </code>


Step 3 init slider

<code>
window.onload = function (){
    let slider = new OnlyBgSlider();
    slider.init(config);
}
</code>

Step 4: customize by config

<code>parentSelector</code>(css Selector) - parent element of your slider
<code>autoplay</code>(boolean) - true/false
<code>arrows</code>(boolean) - true/false
<code>arrows_left</code>(tag) - parent element of your slider
<code>arrows_right</code>(tag) 
<code>speed</code>(ms) - 1000ms
<code>transition</code>(s) - .4s
<code>run</code>(boolean) - true
<code>slides</code>(array) - [];

 
CONFIG EXAMPLE 
<code>
let config = {
    counter: 0,
    parentSelector:'.header__banner',
    autoplay:false,
    arrows: true,
    speed: '1000',
    transition: '.4s',
    run:true,
    slides: slides
}
</code>
<a href="htpps://mashkovtsev.top" target="_blank" >Bandajnyi mir Sergeya Sergeevicha Chudnivtsa</a>
