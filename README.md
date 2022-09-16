# datatable
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="DataTables/datatables.min.css">
</head>
<body>
    <table id="contoh" class="table table-striped">
        <thead>
            <tr>
                <th width="5%">No</th>
                <th width="25%" >Nama</th>
                <th width="15%">Kelas</th>
                <th width="15%">Alamat</th>
                <th width="5%">No HP</th>
            </tr> 
            <tr>
                <td>22</td>
                <td>Lani</td>
                <td>XII K1</td>
                <td>cisitu lama</td>
                <td>085860591187</td>
            </tr>      
            <tr>
                <td>22</td>
                <td>Lani</td>
                <td>XII K1</td>
                <td>cisitu lama</td>
                <td>085860591187</td>
            </tr>    
        </thead>
    </table>
    <script src="DataTables/jQuery-3.6.0/jQuery-3.6.0min.js"></script>
    <script src="DataTables/datatables.min.js"></script>
    <script>
        $(function(){
            var data = [["1", "Lani Meilani", "XII RPL 1", "Alamat", "085860591187"]];
            for (let i = 0; i < 5; j++){
                data.push([i]);
                    data[i].push[j]
            }
            $("#contoh").DataTable({
                responsive : true,
                data: data
            });    
        });
    </script>
</body>
</html>
