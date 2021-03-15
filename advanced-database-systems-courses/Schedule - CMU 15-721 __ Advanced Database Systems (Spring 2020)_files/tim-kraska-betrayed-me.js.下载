$(document).ready(function() {
    
    // Borrowed from https://cs186berkeley.net/js/script.min.js
    $('.next-week-overview').on('click', function() {
        toSlide(parseInt($(this).parent().parent().data('number')) + 1);
    });
    $('.prev-week-overview').on('click', function() {
        toSlide(parseInt($(this).parent().parent().data('number')) - 1);
    });

    function toSlide(number) {
        $('.week-overview').addClass('inactive');
        $('.week-overview[data-number="' + number + '"]').removeClass('inactive');
    }
    
});
