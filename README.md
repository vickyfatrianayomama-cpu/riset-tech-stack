# riset-tech-stack


# Panduan Docker untuk Redmine

## Menjalankan Redmine
Untuk menjalankan Redmine menggunakan Docker Compose, navigasi ke folder yang berisi `docker-compose.yml` dan jalankan perintah berikut:

```bash
docker-compose up -d
```

Redmine akan tersedia di `http://localhost:3000`.

## Menghentikan Redmine
Untuk menghentikan semua container:

```bash
docker-compose down
```

## Restart Redmine
Untuk restart container:

```bash
docker-compose restart
```

## Melihat Log
Untuk melihat log container:

```bash
docker-compose logs
```

Untuk melihat log secara real-time:

```bash
docker-compose logs -f
```

## Menghapus Container, Volume, dan Image
Untuk menghapus semua container, volume, dan image terkait:

```bash
docker-compose down --volumes --rmi all
```

Ini akan menghapus data persistensi (volume) dan image Docker yang digunakan.