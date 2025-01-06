<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pencatatan Keuangan Brilink</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"></link>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100">
    <header class="bg-blue-600 text-white p-4">
        <div class="container mx-auto text-center">
            <h1 class="text-2xl font-bold">Pencatatan Keuangan Brilink</h1>
        </div>
    </header>

    <main class="container mx-auto mt-8 p-4">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
            <section class="bg-white p-6 rounded-lg shadow-lg">
                <h2 class="text-xl font-semibold mb-4">Tambah Transaksi Baru</h2>
                <form class="space-y-4">
                    <div>
                        <label for="tanggal" class="block text-sm font-medium text-gray-700">Tanggal</label>
                        <input type="date" id="tanggal" name="tanggal" class="mt-1 block w-full p-2 border border-gray-300 rounded-md">
                    </div>
                    <div>
                        <label for="deskripsi" class="block text-sm font-medium text-gray-700">Deskripsi</label>
                        <input type="text" id="deskripsi" name="deskripsi" class="mt-1 block w-full p-2 border border-gray-300 rounded-md">
                    </div>
                    <div>
                        <label for="jumlah" class="block text-sm font-medium text-gray-700">Jumlah</label>
                        <input type="number" id="jumlah" name="jumlah" class="mt-1 block w-full p-2 border border-gray-300 rounded-md">
                    </div>
                    <div>
                        <label for="tipe" class="block text-sm font-medium text-gray-700">Tipe</label>
                        <select id="tipe" name="tipe" class="mt-1 block w-full p-2 border border-gray-300 rounded-md">
                            <option value="pemasukan">Pemasukan</option>
                            <option value="pengeluaran">Pengeluaran</option>
                            <option value="biaya_admin_bank">Biaya Admin Bank</option>
                            <option value="biaya_admin_cash">Biaya Admin Cash</option>
                        </select>
                    </div>
                    <div>
                        <label for="keterangan" class="block text-sm font-medium text-gray-700">Keterangan</label>
                        <textarea id="keterangan" name="keterangan" class="mt-1 block w-full p-2 border border-gray-300 rounded-md"></textarea>
                    </div>
                    <button type="submit" class="w-full bg-blue-600 text-white p-2 rounded-md">Tambah Transaksi</button>
                </form>
            </section>

            <section class="bg-white p-6 rounded-lg shadow-lg">
                <h2 class="text-xl font-semibold mb-4">Transaksi Terbaru</h2>
                <table class="min-w-full bg-white">
                    <thead>
                        <tr>
                            <th class="py-2 px-4 border-b">Tanggal</th>
                            <th class="py-2 px-4 border-b">Deskripsi</th>
                            <th class="py-2 px-4 border-b">Jumlah</th>
                            <th class="py-2 px-4 border-b">Tipe</th>
                            <th class="py-2 px-4 border-b">Keterangan</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td class="py-2 px-4 border-b">2023-10-01</td>
                            <td class="py-2 px-4 border-b">Gaji</td>
                            <td class="py-2 px-4 border-b">5000000</td>
                            <td class="py-2 px-4 border-b">Pemasukan</td>
                            <td class="py-2 px-4 border-b">Gaji bulanan dari perusahaan</td>
                        </tr>
                        <tr>
                            <td class="py-2 px-4 border-b">2023-10-02</td>
                            <td class="py-2 px-4 border-b">Belanja Harian</td>
                            <td class="py-2 px-4 border-b">-150000</td>
                            <td class="py-2 px-4 border-b">Pengeluaran</td>
                            <td class="py-2 px-4 border-b">Pembelian kebutuhan sehari-hari</td>
                        </tr>
                        <tr>
                            <td class="py-2 px-4 border-b">2023-10-03</td>
                            <td class="py-2 px-4 border-b">Tagihan Listrik</td>
                            <td class="py-2 px-4 border-b">-100000</td>
                            <td class="py-2 px-4 border-b">Pengeluaran</td>
                            <td class="py-2 px-4 border-b">Pembayaran tagihan listrik bulanan</td>
                        </tr>
                        <tr>
                            <td class="py-2 px-4 border-b">2023-10-04</td>
                            <td class="py-2 px-4 border-b">Proyek Freelance</td>
                            <td class="py-2 px-4 border-b">2000000</td>
                            <td class="py-2 px-4 border-b">Pemasukan</td>
                            <td class="py-2 px-4 border-b">Pendapatan dari proyek freelance</td>
                        </tr>
                        <tr>
                            <td class="py-2 px-4 border-b">2023-10-05</td>
                            <td class="py-2 px-4 border-b">Makan di Luar</td>
                            <td class="py-2 px-4 border-b">-50000</td>
                            <td class="py-2 px-4 border-b">Pengeluaran</td>
                            <td class="py-2 px-4 border-b">Biaya makan di restoran</td>
                        </tr>
                        <tr>
                            <td class="py-2 px-4 border-b">2023-10-06</td>
                            <td class="py-2 px-4 border-b">Biaya Admin Bank</td>
                            <td class="py-2 px-4 border-b">-20000</td>
                            <td class="py-2 px-4 border-b">Biaya Admin Bank</td>
                            <td class="py-2 px-4 border-b">Biaya administrasi bulanan bank</td>
                        </tr>
                        <tr>
                            <td class="py-2 px-4 border-b">2023-10-07</td>
                            <td class="py-2 px-4 border-b">Biaya Admin Cash</td>
                            <td class="py-2 px-4 border-b">-10000</td>
                            <td class="py-2 px-4 border-b">Biaya Admin Cash</td>
                            <td class="py-2 px-4 border-b">Biaya administrasi cash handling</td>
                        </tr>
                    </tbody>
                </table>
            </section>
        </div>
    </main>

    <footer class="bg-blue-600 text-white p-4 mt-8">
        <div class="container mx-auto text-center">
            <p>&copy; 2023 Pencatatan Keuangan Brilink. Hak cipta dilindungi undang-undang.</p>
        </div>
    </footer>
</body>
</html>
