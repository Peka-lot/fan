$(document).ready(function () {
    $(window).scroll(function () {
        var scroll = $(this).scrollTop();

        $('.parallax-bg').each(function () {
            var bgObj = $(this);
            var bgYPos = -(scroll * 0.5);
            var coords = '50% ' + bgYPos + 'px';

            bgObj.css({
                backgroundPosition: coords
            });
        });
    });
});
 