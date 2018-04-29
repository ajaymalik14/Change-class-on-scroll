# Change-class-on-scroll
<pre>
window.addEventListener('scroll', function(){
        var nav = document.getElementById('myna');
        if (document.documentElement.scrollTop || document.body.scrollTop > window.innerHeight) {
                nav.classList.add('nav-bot');
                nav.classList.remove('nav-top');
            } else {
                nav.classList.add('nav-top');
                nav.classList.remove('nav-bot');
            }
    });
</pre>
