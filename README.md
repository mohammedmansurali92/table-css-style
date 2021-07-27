# table-css-style
<title>My css Table</title>
    <style>
        table{
            border: 1px solid black;
            border-collapse: collapse;
            width: 100%;
        }
        th, td{
            border: 1px solid black;
            padding: 5px;
            text-align: center;
        }
        th{
            background-color: greenyellow;
            color: white;
            height: 30px;
            vertical-align: middle;
        }
       
        tr:nth-child(even){
            background-color:gray;
        }
        tr:nth-child(odd){
            background-color:green;
        }
        tr:hover{
            background-color:gold;
        }
    </style>
<body>
    <table>
        <caption>Student Detils</caption>
        <tr>
            <th>Id</th>
            <th>Name</th>
            <th>GPA</th>
            <th>Phone</th>
            <th>Bio</th>
        </tr>
        <tr>
            <td>101</td>
            <td>Towfique</td>
            <td>4.5</td>
            <td>01732233620</td>
            <td> love harold these ah hope, that reverie say heartless a drowsy woe made, in from long the atonement womans but. And nor far heart the perchance were nor who in. There een day of this her oer yet his,.</td>
        </tr>
        <tr>
            <td>102</td>
            <td>Towhid</td>
            <td>4.25</td>
            <td>0564509222</td>
            <td> love harold these ah hope, that reverie say heartless a drowsy woe made, in from long the atonement womans but. And nor far heart the perchance were nor who in. There een day of this her oer yet his,.</td>
        </tr>
        <tr>
            <td>103</td>
            <td>Mony</td>
            <td>3.50</td>
            <td>0564509222</td>
            <td> love harold these ah hope, that reverie say heartless a drowsy woe made, in from long the atonement womans but. And nor far heart the perchance were nor who in. There een day of this her oer yet his,.</td>
        </tr>
        <tr>
            <td>104</td>
            <td>Munmun</td>
            <td>4.25</td>
            <td>0564509222</td>
            <td> love harold these ah hope, that reverie say heartless a drowsy woe made, in from long the atonement womans but. And nor far heart the perchance were nor who in. There een day of this her oer yet his,.</td>
        </tr>
        <tr>
            <td>105</td>
            <td>Tahmina</td>
            <td>3.5</td>
            <td>0564509222</td>
            <td>love harold these ah hope, that reverie say heartless a drowsy woe made, in from long the atonement womans but. And nor far heart the perchance were nor who in. There een day of this her oer yet his,.</td>
        </tr>
    </table>
</body>
