# European Football Clubs

A list of all European football clubs that have participated in European competitions from 2017-18 to 2024-25. 

***NOTE: It does not contain defunct clubs or clubs that currently play in lower leagues than the 2nd division.***

## Structure
The data is structured in a JSON format for easy access and manipulation. The main components are:

- **Countries**: Each country is identified by a unique `id`, a `name`, and a `code`.
- **Clubs**: Each club within a country is also identified by a unique `id` and a `name`.

### Example Structure
```
{
    "id": 16,
    "name": "Faroe Islands",
    "code": "FO",
    "clubs": [
        {
            "id": 1,
            "name": "Víkingur Gøta"
        },
        {
            "id": 2,
            "name": "KÍ"
        },
        {
            "id": 3,
            "name": "NSÍ Runavík"
        },
        {
            "id": 4,
            "name": "B36 Tórshavn"
        },
        {
            "id": 5,
            "name": "HB Tórshavn"
        }
    ]
}
```

## Data Sources
The data is compiled from official UEFA records, tracking the participation of clubs from each UEFA member country in European competitions over the specified period.

## Contribution
Contributions are welcome! Please feel free to submit a pull request or open an issue with any suggestions or improvements.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or issues, please contact [pdfrontend@zohomail.eu](mailto:pdfrontend@zohomail.eu).
