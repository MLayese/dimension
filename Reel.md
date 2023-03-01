---
title: Reel
---

<section>
  <iframe class="image main" width="520" height="300" src="https://www.youtube.com/embed/SC0Ub0Q9SoM" frameborder="0" allowfullscreen></iframe>
	<h4>Sound Design Reel 2023</h4> 
</section>

<!-- <button class="accordion">Section 1</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
  <section>
  <iframe class="image main" width="520" height="300" src="https://www.youtube.com/embed/SC0Ub0Q9SoM" frameborder="0" allowfullscreen></iframe>
	<h4>Sound Design Reel 2023</h4> 
</section>
</div> -->
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
<!-- .accordion {
		@include vendor('appearance', 'none');
		@include vendor('transition', 'background-color #{_duration(transition)} ease-in-out, color #{_duration(transition)} ease-in-out');
		background-color: transparent;
		border-radius: transparent(border-radius);
		border: 0;
		box-shadow: inset 0 0 0 _size(border-width) transparent(border);
		color: _palette(fg-bold) !important;
		cursor: pointer;
		display: inline-block;
		font-size: 0.8rem;
		font-weight: _font(weight);
		height: _size(element-height);
		letter-spacing: _font(letter-spacing);
		line-height: _size(element-height);
		outline: 0;
		padding: 0 1.25rem 0 (1.25rem + (_font(letter-spacing) * 0.5));
		text-align: center;
		text-decoration: none;
		text-transform: uppercase;
		white-space: nowrap;

		&:hover {
			background-color: _palette(border-bg);
		}

		&:active {
			background-color: _palette(border-bg-alt);
		}

		&.icon {
			&:before {
				margin-right: 0.5em;
			}
		}

		&.fit {
			width: 100%;
		}

		&.small {
			font-size: 0.6rem;
			height: (_size(element-height) * 0.75);
			line-height: (_size(element-height) * 0.75);
		}

		&.primary {
			background-color: _palette(fg-bold);
			color: _palette(bg) !important;
			font-weight: _font(weight-bold);

			&:hover {
			}

			&:active {
			}
		}

		&.disabled,
		&:disabled {
			@include vendor('pointer-events', 'none');
			cursor: default;
			opacity: 0.25;
		}
	}

.active, .accordion:hover {
  background-color: _palette(border-bg);
} -->
.accordion {
  		@include vendor('appearance', 'none');
		@include vendor('transition', 'background-color #{_duration(transition)} ease-in-out, color #{_duration(transition)} ease-in-out');
        background: transparent;
  border: none;
  margin: 10px auto 0;
  display: block;
  font-size: 20px;
  outline: none;
  position: relative;
  transition: 0.3s;
  padding: 10px;
		background-color: transparent;
		border-radius: transparent(border-radius);
		border: 0;
		box-shadow: inset 0 0 0 _size(border-width) _palette(border);
		color: _palette(fg-bold) !important; 
<!-- 		//_palette(fg-bold) !important -->
		cursor: pointer;
		display: inline-block;
		font-size: 0.8rem;
		font-weight: _font(weight);
		height: _size(element-height);
		letter-spacing: _font(letter-spacing);
		line-height: _size(element-height);
		outline: 0;
		padding: 0 1.25rem 0 (1.25rem + (_font(letter-spacing) * 0.5));
		text-align: center;
		text-decoration: none;
		text-transform: uppercase;
		white-space: nowrap;
}

.accordion:before{
content: '';
  border-bottom: 1px solid #000;
  padding: 0 10px;
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  margin: 0 auto;
  width: 0;
  transition: 0.3s;
}

.accordion:hover:before {
  width: 100%;
  padding: 0;
}

.panel {
  padding: 0 18px;
  background-color: _palette(border-bg);
<!-- 	_palette(border-bg) -->
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
}
</style>
</head>
<body>

<button class="accordion">Test</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
  <section>
  <iframe class="image main" width="520" height="300" src="https://www.youtube.com/embed/SC0Ub0Q9SoM" frameborder="0" allowfullscreen></iframe>
	<h4>Sound Design Reel 2023</h4> 
</section>
</div>

<button class="accordion">Section 2</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<button class="accordion">Section 3</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.maxHeight) {
      panel.style.maxHeight = null;
    } else {
      panel.style.maxHeight = panel.scrollHeight + "px";
    } 
  });
}
</script>

</body>
</html>
