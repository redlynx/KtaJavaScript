var okUri = 'http://localhost/TotalAgility/DeployedImages/ok-16.png';
var nokUri = 'http://localhost/TotalAgility/DeployedImages/x-mark-16.png';

// the control's ids
var btnCtrlId = "_6A55F20FE77840319468A01364AF2351";
var imgCtrlId = "_250ae408661d4891b535a24f32aade1f";
// the controls themselves
var swapButton = $(".x-btn[id='" + btnCtrlId + "']");
var img = $("img[id='" + imgCtrlId + "']");

// swaps an image source on the click event
swapButton.click(function() {
	var currentImgSrc = img.attr("src");
	if (currentImgSrc == okUri) img.attr("src", nokUri);
	else img.attr("src", okUri);	
});
