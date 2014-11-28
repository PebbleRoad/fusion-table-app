# Google fusion table to Datatables

Display data from Google Fusion tables in table or card format using Datatables

## Demo

[http://pebbleroad.github.io/fusion-table-app/](http://pebbleroad.github.io/fusion-table-app/)

## How to use

Add table markup in your html

    <table class="datatable" cell-spacing="0" width="100%">
    
Make sure to add `data-fusion="FUSION_TABLE_ID"`, ID of the fusion table you want to display

Initialize the app

    $(function(){

        app.init({
            el: $('.datatable'),
            dataSource: '1No1xirmHhmV99FdzCBC32AWAmwZaLuEZ2qAxhUA' // Your google fusion table ID
        })
    })