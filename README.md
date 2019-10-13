# jc_chart
chart project

# use
function and target id

    JC_Chart('canvas_chart_standard',
      {
        title	: "Chart Standard", 
        subtitle: "Periode Apa Aja Boleh"
      },
      {
        "Jakarta"	: 460, 
        "Bandung"	: 386, 
        "Surabaya"	: 250, 
        "Semarang"	: 180, 
        "Tangerang"	: 270, 
        "Medan"		: 280, 
        "Manado"	: 130, 
        "Bekasi"	: 320
      });
      
# full example

    <!DOCTYPE html>
    <html>
    <head>
      <title>JC Chart</title>
      <script type="text/javascript" src="js/standard_chart.js"></script>
    </head>
    <body>

    <div style="width: 100%; height: 350px;">
      <canvas id="canvas_chart_standard"></canvas>
    </div>

    <script type="text/javascript">
      JC_Chart('canvas_chart_standard',
      {
        title	: "Chart Standard", 
        subtitle: "Periode Apa Aja Boleh"
      },
      {
        "Jakarta"	: 460, 
        "Bandung"	: 386, 
        "Surabaya"	: 250, 
        "Semarang"	: 180, 
        "Tangerang"	: 270, 
        "Medan"		: 280, 
        "Manado"	: 130, 
        "Bekasi"	: 320
      });
    </script>

    </body>
    </html>
