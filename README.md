<p align="center">
    <img src="https://github.com/rose-pine/rose-pine-theme/raw/main/assets/icon.png" width="80" />
    <h2 align="center">Rosé Pine for SQL Developer</h2>
</p>

<p align="center">All natural pine, faux fur and a bit of soho vibes for the classy minimalist</p>

## Installation

You can use the same instructions provided by the [Dracula Theme for Oracle SQL Developer](https://draculatheme.com/oracle-sql-developer):

1. Close SQL Developer. This is important. If you modify the scheme file while SQL Developer is open, your changes won't be saved.
2. Locate file dtcache.xml in the [SQL Developer's settings directory](https://docs.oracle.com/en/database/oracle/sql-developer/19.1/rptig/installing-sql-developer.html#GUID-16F0A7C3-6EC1-4176-9B15-FE4AA8D70D5F).

    **Windows:**

    `%APPDATA%\SQL Developer\systemn.n.n.n.n.n\o.ide.n.n.n.n.n.n.n`

    Example:

    `C:\Users\dracula\AppData\Roaming\SQL Developer\system3.2.20.09.87\o.ide.11.1.1.4.37.59.48`

    **Linux or Mac OS X:**

    `~/.sqldeveloper/systemn.n.n.n.n.n/o.ide.n.n.n.n.n.n.n`

    Example:

    `~/.sqldeveloper/system19.1.0.094.2042/o.ide.13.0.0.1.42.170225.201`

3. Locate <schemeMap> tag inside dtcache.xml file.
<img width="976" height="406" alt="Image" src="https://github.com/user-attachments/assets/cd5bd3dd-b0b2-4bf9-bcce-ebba2be0d2ff" />
    

 
## Gallery

### Rosé Pine

<img width="256" alt="Rosé Pine with App" src="https://github.com/user-attachments/assets/3d9df6a3-0ee3-43f2-b934-83cf8f2806c2" />

### Rosé Pine Moon

<img width="256" alt="Rosé Pine Moon with App" src="https://github.com/user-attachments/assets/0acf279b-492c-4d75-acba-9de1d6cc8fcb" />

### Rosé Pine Dawn

<img width="256" alt="Rosé Pine Dawn with App" src="https://github.com/user-attachments/assets/fb1b1d16-55e8-45db-b388-7c25250b8022" />

## Thanks to

- [You, it's you!](https://github.com/<username>)

## Contributing

<!-- BLOOM_BUILD_START -->
This theme was built using [bloom](https://github.com/rose-pine/rose-pine-bloom):

```sh
bloom build template.yaml --output dist --prefix $ --format hex
```
<!-- BLOOM_BUILD_END -->
