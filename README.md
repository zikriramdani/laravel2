![result](https://github.com/zikriramdani/laravel2/blob/main/screencaptures.png)

<b>Simple Blog System With Laravel</b><br>
<hr>
<p>
    Aplikasi ini mempunyai fitur : 
</p>
<ul>
        <li> Gutenberg Editor like Wordpress</li>
        <li> Page Builder</li>
        <li> Menu Manager</li>
</ul>

<p>Aplikasi ini dibuat menggunakan Framework Laravel 5 dengan tambahan package-package lain, seperti :<br>
1) Bootstrap 4,<br>
2) SweetAlert,<br>
3) Datatables,<br>
4) Laraberg - Wordpress Gutenberg Editor [https://github.com/VanOns/laraberg](https://github.com/VanOns/laraberg)<br>
5) GrapeJs - Page Builder [http://grapesjs.com/](http://grapesjs.com/)<br>
6) Bootstrap 4 Block For GrapeJs [https://github.com/kaoz70/grapesjs-blocks-bootstrap4](https://github.com/kaoz70/grapesjs-blocks-bootstrap4)<br>
7) Laravel Filemanager [https://github.com/UniSharp/laravel-filemanager](https://github.com/UniSharp/laravel-filemanager)<br>
8) Disqus - Comment System [https://disqus.com/](https://disqus.com/)<br>
9) WMENU Builder wordpres menu builder for laravel [https://github.com/harimayco/wmenu-builder](https://github.com/harimayco/wmenu-builder)
</p>

Cara menjalankan Aplikasi : 
- Simpan Project di /htdocs (kalau pake xampp)
- jalankan "composer install" di dalam terminal/cmd
- jalankan "npm install" di dalam terminal/cmd
- buka folder project, copykan .env.example, menjadi .env
- isi DB_DATABASE, DB_USERNAME, DB_PASSWORD, sesuaikan dengan settingan database kamu
- buat akun [http://disqus.com/](http://disqus.com/) untuk mengisi `EMBED_DISQUS`
- di dalam directory project buka terminal, ketikan "php artisan key:generate"
- di dalam directory project buka terminal, ketikan "php artisan migrate"
- di dalam directory project buka terminal, ketikan "php artisan db:seed"
- di dalam directory project buka terminal, ketikan "php artisan serve"
- buka browser, ketikan url "localhost:8000"

<hr>
<h5>Account Created : <h5>
link login "/admin/login"
username : admin@mail.com<br>
password : 12345678

***sistem ini belum final jadi setiap ada perubahan database harus menjalankan migration dari awal lagi dengan `php artisan migrate:fresh`***