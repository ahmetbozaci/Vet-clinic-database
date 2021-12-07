![](https://img.shields.io/badge/Microverse-blueviolet)

# Vet Clinic Database

## Built With

- Sql

> We use `explain analyze`  for some queries. 
> Checked execution time before index and after add index.

**Here are results;**

1. `SELECT COUNT(*) FROM visits where animal_id = 4;`

#### BEFORE
![animal-analyze-before](https://user-images.githubusercontent.com/38635158/145065412-2b4d8803-0ff6-4398-b7b6-64c851570cab.png)

#### AFTER add index
![animal-analyze-after](https://user-images.githubusercontent.com/38635158/145065555-a68d9b8d-3fab-4b88-8790-d003ba282369.png)

2. `SELECT * FROM visits where vet_id = 2;`
#### BEFORE
![vet-analyze-before](https://user-images.githubusercontent.com/38635158/145065782-444d4b45-cb64-45cc-b864-98bcab2f24f4.png)

#### AFTER add index
![vet-analyze-after](https://user-images.githubusercontent.com/38635158/145065814-4b9486e6-d511-4a35-a980-e0bf69e82344.png)

3. `SELECT * FROM owners where email = 'owner_18327@mail.com';`

#### BEFORE
![email-analyze-before](https://user-images.githubusercontent.com/38635158/145067317-fe764c8d-d3cb-48ae-8960-0e0a999e1565.png)

#### AFTER add index
![email-analyze-before](https://user-images.githubusercontent.com/38635158/145067599-f8bdfe9c-a616-4f8a-99cb-e8fb4109f4fd.png)



## Setup
- Clone this project
```
- $ git clone `$ https://github.com/ahmetbozaci/Vet-clinic-database.git`
- $ cd vet-clinic-database
```

## Authors

👤 **Ahmet Bozacı**
- Github:[ahmetbozaci](https://github.com/ahmetbozaci)
- Twitter:[ahmtbozaci](https://twitter.com/ahmtbozaci)
- LinkedIn:[ahmetbozaci](https://www.linkedin.com/in/ahmetbozaci/)

👤 **Bishoy Samwel Faheem**
- GitHub: [@Bishoy Samwel Faheem](https://github.com/Bishoy-Samwel)
- LinkedIn: [Bishoy Samwel](https://www.linkedin.com/in/bishoy-samwuel-ss/)
- Twitter: [@bisho](https://twitter.com/BishoFaheem15)

👤 **Luqman Musah**

- GitHub: [@luqmanmusah](https://github.com/luqmanmusah)
- LinkedIn: [Luqman Musah](https://www.linkedin.com/in/luqman-musah/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

* This project is [MIT](./LICENSE) licensed.
