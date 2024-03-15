---
title: Garmin watch wizard
sidebar_position: 3
---
<div>
    At the time of downloading, Garmin had a total of 
    <span id="productCountPlaceholder"></span> watches on their web pages.

    These watches had a total of <span id="specificationCountPlaceholder"></span> specifications to choose
    between.

    If you are considering buying a Garmin watch on Amazon, it would be great if you can use [my affiliate link](https://www.amazon.com/s?k=garmin+watch&rh=n%3A10048700011%2Cp_89%3AGarmin&dc=&ds=v1%3ArASg7keBPl%2FyftcULH%2BO9J350YEc5scEqUMrzuOOxWs&crid=15846T301L64X&qid=1710524151&rnid=2528832011&sprefix=garmin%2Caps%2C263&linkCode=ll2&tag=garminwizard-20&linkId=88cfd20c5298e3e646101da1279bafb2&language=en_US&ref_=as_li_ss_tl")
</div>

<div id="loadingIndicator">
    <div></div>
</div>

<div id="garminwizard">
    <div className="tab">
    <button className="tablinks" data-page="Page1" id="defaultOpen">
    <h2 id="requirements-title">Specifications<span id="numberOfUniqueSpecs" className="garminbadgehidden"></span></h2>
    </button>
    <button className="tablinks" data-page="Page2"><h2>Matching products<span id="matchingProducts" className="garminbadgehidden"></span></h2></button>
    </div>
    <div id="Page1" className="tabcontent">
        <button id="expand-all-button">Expand All</button>
        <button id="collapse-all-button">Collapse All</button>
        <button id="check-all-button">Check All</button>
        <button id="uncheck-all-button">Uncheck All</button>
        <div id="garmin">
        </div>
    </div>
    <div id="Page2" className="tabcontent">
        <div id="garmin-result"></div>
    </div>
</div>