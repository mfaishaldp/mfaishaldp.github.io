# myBro Apps

## indexRegistration.html
### Id
1. name
2. username
3. passwd
4. emails
### Feature
1. user dapat melakukan registrasi.
2. apabila username telah terdaftar, tidak dapat didaftarkan lagi.
3. user harus lengkap mengisi seluruh form.
### Local Storage
1. userRegisteredLocal
``` 
[{
  "name": "doni",
  "username": "doniagung",
  "password": "doniagung123",
  "email": "doniagung@gmail.com"
},
{
  "name": "qwf",
  "username": "qwf",
  "password": "qwf",
  "email": "qwf"
}]
```


## indexLogin.html
### Id
1. username
2. passwd
### Feature
1. user dapat memasukan username dan password sesuai dengan yang di registrasikan.
### Session Storage
1. currentLoggedIn
```
{
  "username": "doniagung",
  "name": "doni",
  "email": "doniagung@gmail.com"
}
```

## indexLanding.html
### Id
1. welcome
2. target
3. keterangan
4. tabung
5. saldoPerTarget
### Feature
1. user dapat submit target / update target.
2. user dapat submit transaksi penabungan dengan "keterangan" dan "jumlah saldo".
3. user dapat melihat keseluruhan transaksi pada table.
4. user dapat melihat total saldo/target -nya
5. user dapat melakukan delete account
### Local Storage
1. userTabungLocal
```
[
  {
    "username": "doniagung",
    "histories": [
      {
        "date": "2/2/2025 15:41:33",
        "keterangan": "qwf",
        "saldo": "3"
      },
      {
        "date": "2/2/2025 15:41:39",
        "keterangan": "werg",
        "saldo": "36"
      }
    ]
  },
  {
    "username": "k",
    "histories": [
        {
        "date": "2/2/2025 17:34:10",
        "keterangan": "we",
        "saldo": "2"
        }
    ]
  }
]
```
2. userTargetLocal
```
[
  {
    "username": "doniagung",
    "target": "20000"
  },
  {
    "username": "k",
    "target": "22"
  }
]
```