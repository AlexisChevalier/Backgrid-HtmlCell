Backgrid-Custom-Cells
=====================

Custom backgrid cell for HTML Content

Go to http://backgridjs.com/ for more information on this library.

How to use it :
<pre>
{
    name: "Model parameter name",
    label: "Column name",
    formatter: _.extend({}, Backgrid.CellFormatter.prototype, {
        fromRaw: function (rawValue) {
            return 'HTML CONTENT';
            //You can use rawValue to custom your html, you can change this value using the name parameter.
        }
    }),
    cell: "html"
}
</pre>
