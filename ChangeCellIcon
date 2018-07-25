// get all cells for a specific column
// this column holds the image
var imgColId = '_AC9C582D18554E5A98622BE52927FE3D';
// this column holds values we need to check
var chkColId = '_AEF2781A6F3B4DAABA660E5B78EE3DF1';
var imgCells = $("[data-columnid=" + imgColId + "]");

// icons we want to apply
var okUri = 'http://localhost/TotalAgility/DeployedImages/ok-16.png';
var nokUri = 'http://localhost/TotalAgility/DeployedImages/x-mark-16.png';
	

// loop all cells
imgCells.each(function(){
	// retrieve the value form another cell within the same row (i.e. another td)
	// then, get the text contained within the cell
	var chkCell = $(this).prevAll("[data-columnid=" + chkColId + "]");
	var txtToCheck = chkCell.find("[id*='tblCountries']").text();
	if (txtToCheck.startsWith('A')) {
		// find the contained img tag and change it
		$(this).find('img').attr('src', nokUri);
	}
});
