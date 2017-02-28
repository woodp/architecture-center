<link href="/azure/architecture/_css/pnp.css" type="text/css" rel="stylesheet" />
<nav class="categories"></nav>
<nav class="series"></nav>
<script type="text/javascript">
(function () {
var nav = $('nav.series');
var prev = $('meta[name="pnp.series.prev"]');
var next = $('meta[name="pnp.series.next"]');
var title = $('meta[name="pnp.series.title"]');
if (prev.length) {
    nav.append( $('<a class="prev" href="' + prev.attr('content') +'">« Previous</a>') );
}
if (next.length) {
    nav.append( $('<a class="next" href="' + next.attr('content') +'">Next »</a>') );
}
if (title.length) {
    $('h1').prepend( $('<span class="series">' + title.attr('content') +  '</span>') );
}
// cloud design patterns
var nav = $('nav.categories');
var categories = $('meta[name="pnp.pattern.categories"]');
categories.each(function(index){
    var el = $(this);
    var slug = el.attr('content');
    var img = '<img src="/azure/architecture/patterns/_images/category/' + slug + '.svg" alt="' + slug +'" />';
    nav.append( $('<a href="category/' + slug +'">' + img + '</a>') );
});
})();
</script>