$(document).on('mouseover', '.topMenu span', function () {
    $('.dept02').slideDown(200);
});
$(document).on('mouseover', 'div', function () {
    if (!$(this).hasClass('topMenu')) {
        $('.dept02').slideUp(200);
    }
});


//출처: https://dororongju.tistory.com/29 [웹 개발 메모장]
