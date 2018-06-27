---
layout: page
title: Results
permalink: /results/
---

<h2 class="section-heading">2018</h2>
<table class="table">
    <thead>
        <tr>
            <th>Date</th>
            <th>Event</th>
            <th>Location</th>
            <th>Class</th>
            <th>Result</th>
            <th>Race Report</th>
            <th>Video</th>
        </tr>
    </thead>
    <tbody>
    {% for result in site.data.2018_results %}
        <tr>
            <td>{{result.date}}</td>
            <td>{{result.event}}</td>
            <td>{{result.location}}</td>
            <td>{{result.class}}</td>
            <td>{{result.result}}</td>
            {% if result.report %}
            <td><a href="{{result.report}}">Report</a></td>
            {% else %}
            <td>N/A</td>
            {% endif %}
            {% if result.video %}
            <td><a href="{{result.video}}">Video</a></td>
            {% else %}
            <td>N/A</td>
            {% endif %}
        </tr>
    {% endfor %}
    </tbody>
</table>


<h2 class="section-heading">2017</h2>
<table class="table">
    <thead>
        <tr>
            <th>Date</th>
            <th>Event</th>
            <th>Location</th>
            <th>Class</th>
            <th>Result</th>
            <th>Race Report</th>
            <th>Video</th>
        </tr>
    </thead>
    <tbody>
    {% for result in site.data.2017_results %}
        <tr>
            <td>{{result.date}}</td>
            <td>{{result.event}}</td>
            <td>{{result.location}}</td>
            <td>{{result.class}}</td>
            <td>{{result.result}}</td>
            {% if result.report %}
            <td><a href="{{result.report}}">Report</a></td>
            {% else %}
            <td>N/A</td>
            {% endif %}
            {% if result.video %}
            <td><a href="{{result.video}}">Video</a></td>
            {% else %}
            <td>N/A</td>
            {% endif %}
        </tr>
    {% endfor %}
    </tbody>
</table>


<h2 class="section-heading">2016</h2>

<table class="table">
    <thead>
        <tr>
        <th>Date</th>
        <th>Series</th>
        <th>Round</th>
        <th>Location</th>
        <th>Class</th>
        <th>Result</th>
        <th>Race Report</th>
        </tr>
    </thead>
    <tbody>
        <tr>
        <td>2016/08/27</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 5</td>
        <td>Pacific Raceways</td>
        <td>Clubman Qualifer</td>
        <td>DQ (1:33.981)</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-5-race-report/10154367581650729">Report</a></td>
        </tr>
        <tr>
        <td>2016/08/27</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 5</td>
        <td>Pacific Raceways</td>
        <td>600SBK</td>
        <td>15th</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-5-race-report/10154367581650729">Report</a></td>
        </tr>
        <tr>
        <td>2016/08/27</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 5</td>
        <td>Pacific Raceways</td>
        <td>600TFS</td>
        <td>9th</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-5-race-report/10154367581650729">Report</a></td>
        </tr>
        <tr>
        <td>2016/08/26</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 5</td>
        <td>Pacific Raceways</td>
        <td>Clubman Qualifier)</td>
        <td>4th</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-5-race-report/10154367581650729">Report</a></td>
        </tr>
        <tr>
        <td>2016/08/26</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 5</td>
        <td>Pacific Raceways</td>
        <td>600SS</td>
        <td>20th</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-5-race-report/10154367581650729">Report</a></td>
        </tr>
        <tr>
        <td>2016/07/24</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
            +
            <a href="http://omrra.com"><img src="../img/OMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 4</td>
        <td>Portland International Raceway</td>
        <td>600SBK</td>
        <td>22nd</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrraommra-round-4-race-report/10154278806255729">Report</a></td>
        </tr>
        <tr>
        <td>2016/07/24</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
            +
            <a href="http://omrra.com"><img src="../img/OMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 4</td>
        <td>Portland International Raceway</td>
        <td>600TFS</td>
        <td>7th</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrraommra-round-4-race-report/10154278806255729">Report</a></td>
        </tr>
        <tr>
        <td>2016/07/24</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
            +
            <a href="http://omrra.com"><img src="../img/OMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 4</td>
        <td>Portland International Raceway</td>
        <td>Open Sportsman</td>
        <td>33rd</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrraommra-round-4-race-report/10154278806255729">Report</a></td>
        </tr>
        <tr>
        <td>2016/07/23</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
            +
            <a href="http://omrra.com"><img src="../img/OMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 4</td>
        <td>Portland International Raceway</td>
        <td>600SS</td>
        <td>30th</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrraommra-round-4-race-report/10154278806255729">Report</a></td>
        </tr>
        <tr>
        <td>2016/07/23</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
            +
            <a href="http://omrra.com"><img src="../img/OMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 4</td>
        <td>Portland International Raceway</td>
        <td>Open Sportsman</td>
        <td>26th</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrraommra-round-4-race-report/10154278806255729">Report</a></td>
        </tr>
        <tr>
        <td>2016/05/29</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 2</td>
        <td>The Ridge Motorsports Park</td>
        <td>Clubman Qualifer</td>
        <td>22nd</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-2-race-report/10154148470545729">Report</a></td>
        </tr>
        <tr>
        <td>2016/05/29</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 2</td>
        <td>The Ridge Motorsports Park</td>
        <td>600SBK</td>
        <td>DNF (Electrical Failure)</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-2-race-report/10154148470545729">Report</a></td>
        </tr>
        <tr>
        <td>2016/05/29</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 2</td>
        <td>The Ridge Motorsports Park</td>
        <td>600TFS</td>
        <td>12th</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-2-race-report/10154148470545729">Report</a></td>
        </tr>
        <tr>
        <td>2016/05/28</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 2</td>
        <td>The Ridge Motorsports Park</td>
        <td>Clubman Qualifier</td>
        <td>7th</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-2-race-report/10154148470545729">Report</a></td>
        </tr>
        <tr>
        <td>2016/05/28</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 2</td>
        <td>The Ridge Motorsports Park</td>
        <td>600SS</td>
        <td>11th</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-2-race-report/10154148470545729">Report</a></td>
        </tr>
        <tr>
        <td>2016/04/23</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 1</td>
        <td>Pacific Raceways</td>
        <td>750 SS</td>
        <td>22nd</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-1-race-report/10154148496450729">Report</a></td>
        </tr>
        <tr>
        <td>2016/04/23</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 1</td>
        <td>Pacific Raceways</td>
        <td>600 SS</td>
        <td>14th</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-1-race-report/10154148496450729">Report</a></td>
        </tr>
        <tr>
        <td>2016/04/23</td>
        <td>
            <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 1</td>
        <td>Pacific Raceways</td>
        <td>750 SS</td>
        <td>14th</td>
        <td><a href="https://www.facebook.com/notes/chris-wilcox/2016-wmrra-round-1-race-report/10154148496450729">Report</a></td>
        </tr>
    </tbody>
</table>

<h2 class="section-heading">2015</h2>
<table class="table">
    <thead>
    <tr>
        <th>Date</th>
        <th>Series</th>
        <th>Round</th>
        <th>Location</th>
        <th>Class</th>
        <th>Result</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>2015/09/19</td>
        <td>
        <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        +
        <a href="http://omrra.com"><img src="../img/OMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 6</td>
        <td>Portland International Raceway</td>
        <td>Novice 600cc</td>
        <td>4th</td>
    </tr>
    <tr>
        <td>2015/09/19</td>
        <td>
        <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        +
        <a href="http://omrra.com"><img src="../img/OMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 6</td>
        <td>Portland International Raceway</td>
        <td>Open Sportsman</td>
        <td>14th</td>
    </tr>
    <tr>
        <td>2015/09/18</td>
        <td>
        <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        +
        <a href="http://omrra.com"><img src="../img/OMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 6</td>
        <td>Portland International Raceway</td>
        <td>Novice 600cc</td>
        <td>6th</td>
    </tr>
    <tr>
        <td>2015/09/19</td>
        <td>
        <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        +
        <a href="http://omrra.com"><img src="../img/OMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 6</td>
        <td>Portland International Raceway</td>
        <td>Open Sportsman</td>
        <td>16th</td>
    </tr>
    <tr>
        <td>2015/07/19</td>
        <td>
        <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 4</td>
        <td>Pacific Raceways</td>
        <td>Novice 600cc</td>
        <td>6th</td>
    </tr>
    <tr>
        <td>2015/07/18</td>
        <td>
        <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 4</td>
        <td>Pacific Raceways</td>
        <td>Novice 600cc</td>
        <td>9th</td>
    </tr>
    <tr>
        <td>2015/06/28</td>
        <td>
        <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 3</td>
        <td>The Ridge Motorsports Park</td>
        <td>Novice 600cc</td>
        <td>4th</td>
    </tr>
    <tr>
        <td>2015/06/27</td>
        <td>
        <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 3</td>
        <td>The Ridge Motorsports Park</td>
        <td>Novice 600cc</td>
        <td>4th</td>
    </tr>
    <tr>
        <td>2015/05/24</td>
        <td>
        <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 2</td>
        <td>The Ridge Motorsports Park</td>
        <td>Novice 600cc</td>
        <td>7th</td>
    </tr>
    <tr>
        <td>2015/05/23</td>
        <td>
        <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 2</td>
        <td>The Ridge Motorsports Park</td>
        <td>Novice 600cc</td>
        <td>5th</td>
    </tr>
    <tr>
        <td>2015/04/26</td>
        <td>
        <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 1</td>
        <td>Pacific Raceways</td>
        <td>Novice 600cc</td>
        <td>7th</td>
    </tr>
    <tr>
        <td>2015/04/25</td>
        <td>
        <a href="http://wmrra.com"><img src="../img/WMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 1</td>
        <td>Pacific Raceways</td>
        <td>Novice 600cc</td>
        <td>12th</td>
    </tr>
    <tr>
        <td>2015/04/18</td>
        <td>
        <a href="http://omrra.com"><img src="../img/OMRRA-logo.jpg" height="25"/></a>
        </td>
        <td>Round 1</td>
        <td>Portland International Raceway</td>
        <td>Novice 600cc</td>
        <td>6th</td>
    </tr>
    </tbody>
</table>
