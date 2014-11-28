# Google Fusion Tables to responsive, searchable HTML tables

Display data from Google Fusion tables in table or card format using Datatables

## Demo

[http://pebbleroad.github.io/fusion-table-app/](http://pebbleroad.github.io/fusion-table-app/)

## How to use

1. Add table markup in your html

        <table class="datatable" cell-spacing="0" width="100%">
    

2. Initialize the app

        $(function(){

            app.init({
                el: $('.datatable'),
                dataSource: '1No1xirmHhmV99FdzCBC32AWAmwZaLuEZ2qAxhUA' // Your google fusion table ID
            })
        })
