////////////////////////////////////////////////////////
Read more exapandable content

<button id="learnMoreBtn" class="bold-heading font-red decoration-none">
    Read More About Me
</button>
<div id="moreInfo" class="hidden">
.....content here .....
</div>

/////////////////////////////////////////////////////////



////////////////////////////////////////////////////////
Slider or carousel

<div class="class-name">
    <div class="slider-item-class">
        content goes here
    </div>
    <div class="slider-item-class">
        content goes here
    </div>
    <div class="slider-item-class">
        content goes here
    </div>
    <div class="slider-item-class">
        content goes here
    </div>
</div>


    <script>
      $(document).ready(function () {
        $(".class-name").owlCarousel({
          loop: true,
          dots: true,
          autoplay: true,
          autoplayTimeout: 5000,
          autoplayHoverPause: true,
          responsive: {
            0: {
              items: 1,
            },
            768: {
              items: 2,
            },
            1000: {
              items: 4,
            },
          },
        });
      });
    </script>

/////////////////////////////////////////////////////////


////////////////////////////////////////////////////////
Tabs

<div class="tabs">
    <button class="tab-link active" onclick="openTab(event, 'Tab-Name')">
        Tab Name
    </button>
    <button class="tab-link" onclick="openTab(event, 'Tab-Name-2')">
        Tab Name 2
    </button>
    <button class="tab-link" onclick="openTab(event, 'Tab-Name-3')">
        Tab Name 3
    </button>
</div>


<div id="Tab-Name" class="tab-content">
    Content goes here
</div>
<div id="Tab-Name-2" class="tab-content" style="display: none">
    Content goes here
</div>
<div id="Tab-Name-3" class="tab-content" style="display: none">
    Content goes here
</div>


/////////////////////////////////////////////////////////

91 = 1
80 = 2
92 = 3
97 = 5
98 = 6