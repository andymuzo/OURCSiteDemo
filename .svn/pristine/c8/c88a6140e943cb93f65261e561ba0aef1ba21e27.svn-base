window.onscroll=function(){
	// getting position from scroll top taken from:
	// http://stackoverflow.com/questions/11193453/find-the-vertical-position-of-scrollbar-without-jquery
	var scrollTop = (window.pageYOffset !== undefined) ? window.pageYOffset : (document.documentElement || document.body.parentNode || document.body).scrollTop;
	// check to see if the header has been scrolled past
	if (scrollTop >= 200) {
		// fix the navigation to the top of the screen
		document.getElementById("nav_bar").className = "nav_bar_fixed";
	} else {
		// attach the navigation to the bottom of the page header
		document.getElementById("nav_bar").className = "nav_bar_moving";
	}
}

