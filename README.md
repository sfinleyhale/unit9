# unit9
Unit 9 Assignment

<script>
var wordItems = document.body.getElementsByTagName("strong")[0];

wordItems.addEventListener("mouseover", function(event) {
	if (!isInside(event.relatedTarget, wordItems))
	wordItems.style.color = "red";
});
wordItems.addEventListener("mouseout", function(event)) {
	if (!isInside(event.relatedTarget, wordItems))
	wordItems.style.color = " ";
}
</script>
