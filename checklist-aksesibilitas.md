# Checklist Ketentuan Praktikum 1

## ✅ Struktur HTML5 minimum lengkap

```html
<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 1</title>
</head>

<body>
    ...
</body>

</html>
```

## ✅ Radio/checkbox dikelompokkan dengan fieldset dan legend

```html
<fieldset>
    <legend>Jenis Kelamin:</legend>
    <input type="radio" name="jenis-kelamin" id="laki-laki" required>
    <label for="laki-laki">Laki-laki</label><br>
    <input type="radio" name="jenis-kelamin" id="perempuan" required>
    <label for="perempuan">Perempuan</label><br>
</fieldset>
```

## ✅ Elemen semantik digunakan tepat (header, nav, main, section, footer)

```html
<header>
    <h1>Asisten AI Untuk UMKM</h1>
    <p>Selamat datang di halaman asisten AI untuk UMKM</p>
</header>

<nav>
    <a href="#profile">Profile</a><br>
    <a href="#formdata">Form</a>
</nav>

<main>
    <section id="profile">
        <h2>Ahmad Rassya Maulana</h2>
        <p>20250140157</p>
    </section>

    <section id="formdata">
        ...
    </section>

    <section id="gambar">
        ...
    </section>
</main>

<footer>
    <p>&copy; 2026 Ahmad Rassya Maulana - 20250140157</p>
</footer>
```

## ✅ Heading berurutan dan halaman memiliki title

```html
<title>Praktikum 1</title>
```

```html
<h1>Asisten AI Untuk UMKM</h1>
...
<h2>Ahmad Rassya Maulana</h2>
...
<h2>Form Pendaftaran</h2>
...
<h2>Logo</h2>
```

## ✅ Form memiliki label, id, name, dan required bila perlu

```html
<form action="#">
    <label for="name">Masukkan nama anda:</label>
    <input type="text" id="name" name="name" required><br><br>

    <fieldset>
        <legend>Jenis Kelamin:</legend>
        <input type="radio" name="jenis-kelamin" id="laki-laki" required>
        <label for="laki-laki">Laki-laki</label><br>
        <input type="radio" name="jenis-kelamin" id="perempuan" required>
        <label for="perempuan">Perempuan</label><br>
    </fieldset><br>

    <input type="submit" value="Submit">
</form>
```

## ✅ Setiap gambar bermakna memiliki alt text

```html
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRRYqxevuHys9QU-F_OfIi4Co2a_zqFtDzCT8BzQK2-eTz6dSn2E0pYBWQF&s=10"
    alt="Logo UMKM Komunitas Indonesia">
<img src="logo-umkm-ai.png"
    alt="Logo Asisten AI Untuk UMKM berbentuk ikon robot yang sedang membantu pelaku usaha kecil">
```