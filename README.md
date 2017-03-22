CREDITS:

Free dummy-data JSON generator
http://www.json-generator.com/

jQuery Plugin for generating table elements using JSON data
https://github.com/shabeer-ali-m/jPut 


    {
  name: '{{firstName()}} {{surname()}}', 
  technicianName: '{{firstName()}} {{surname()}}', 
  orderDate: '{{date(new Date(2014, 0, 1), new Date(), "YYYY-MM-dd")}}',    apptType: function (tags) {
      var aptyps = ['QUOTE', 'INSURANCE', 'REPAIR', 'WARRANTY'];
      return aptyps[tags.integer(0,Math.random()*aptyps.length)];
    }, 
  cellPhone: '{{phone()}}', 
  email: '{{email()}}', 
  orderStatusOne:
    ['In Progress'],
    orderStatusTwo: ['Cancelled'], 
        orderStatusThree:['Done']
     }

