<!DOCTYPE html>
<html>
<head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
        .table thead th {
            background-color: #dbeafe;   /* light blue */
            font-weight: bold;
        }

        /* Push status badges to the right */
        .status-col {
            text-align: right;
            width: 150px;
        }
    </style>
</head>

<body class="p-4">

    <table class="table table-bordered">
        <thead>
            <tr>
                <th>Number</th>
                <th>Customer</th>
                <th>Issue</th>
                <th class="status-col">Status</th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <td>6</td>
                <td>jdbh;IHCOHWDHI</td>
                <td>Closed Issue</td>
                <td class="status-col"><span class="badge bg-success">Closed</span></td>
            </tr>

            <tr>
                <td>5</td>
                <td>SIPR Account</td>
                <td>Account Issue</td>
                <td class="status-col"><span class="badge bg-warning text-dark">In Progress</span></td>
            </tr>

            <tr>
                <td>4</td>
                <td>software issue</td>
                <td>Software</td>
                <td class="status-col"><span class="badge bg-success">Closed</span></td>
            </tr>

            <tr>
                <td>3</td>
                <td>car issue</td>
                <td>Vehicle</td>
                <td class="status-col"><span class="badge bg-danger">Open</span></td>
            </tr>

            <tr>
                <td>2</td>
                <td>user issue</td>
                <td>User</td>
                <td class="status-col"><span class="badge bg-danger">Open</span></td>
            </tr>

            <tr>
                <td>1</td>
                <td>dell issue</td>
                <td>Hardware</td>
                <td class="status-col"><span class="badge bg-success">Closed</span></td>
            </tr>

        </tbody>
    </table>

</body>
</html>
