# Keterampilan Umum

## Penulis: [joulephicar](https://github.com/joulephicar)
## Daftar Isi:

| Keterampilan Umum                                |
| ------------------------------------------------ |
| [The Factory’s Secret](#1-the-factorys-secret-1) |
| [2Warm](#2-2warm-50)                             |
| [Lets Warm Up](#3-lets-warm-up-50)               |
| [Warmed Up](#4-warmed-up-50)                     |
| [Bases](#5-bases-50)                             |
| [First Grep](#6-first-grep-50)                   |
| [Resources](#7-resources-50)                     |

---
## 1. The Factory’s Secret (1)

### Soal:

There appear to be some mysterious glyphs hidden inside this [abandoned factory](https://2019game.picoctf.com/game)... I wonder what would happen if you collected them all?

### Pembahasan:

## 2. 2Warm (50)

### Soal:

Can you convert the number 42 (base 10) to binary (base 2)?

### Pembahasan:

Kita dapat menggunakan *tools online* maupun kalkulator bawaan OS (Windows maupun Linux). Selain itu, kita bisa melakukan konversi memakai python dengan fungsi <code>bin()</code> berikut contohnya di ipython.

```py
In [1]: bin(42)                                           
Out[1]: '0b101010'
```

<details>
  <summary>Tekan untuk melihat flag</summary>
  
  ```
  picoCTF{101010}
  ```
</details>

## 3. Lets Warm Up (50)

### Soal:

If I told you a word started with <code>0x70</code> in hexadecimal, what would it start with in ASCII?

### Pembahasan:

Sama seperti soal sebelumnya, untuk mengubah heksadesimal ke [ASCII](https://duckduckgo.com/?q=ascii) dapat menggunakan kalkulator maupun bahasa python. Untuk bahasa python kita dapat menggunakan fungsi <code>chr()</code>

```py
In [1]: chr(0x70)
Out[1]: 'p'
```

<details>
  <summary>Tekan untuk melihat flag</summary>
  
  ```
  picoCTF{p}
  ```
</details>

## 4. Warmed Up (50)

### Soal:

What is 0x3D (base 16) in decimal (base 10).

### Pembahasan:

Seperti biasa, kita dapat menggunakan python dengan langsung mengetik "0x3d" di interpreternya.

```py
In [1]: 0x3d                                             
Out[1]: 61
```

<details>
  <summary>Tekan untuk melihat flag</summary>
  
  ```
  picoCTF{61}
  ```
</details>

## 5. Bases (50)

### Soal:

### Pembahasan:

## 6. First Grep (50)

### Soal:

### Pembahasan:

## 7. Resources (50)

### Soal:

### Pembahasan:
