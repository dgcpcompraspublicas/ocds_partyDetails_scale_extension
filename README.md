# Party details - Scale

This extension adds a scale field to the parties.details object. The values of the categories are defined according to the regulations and standards of the Ministry of Industry and sme in the Dominican Republic.

- Micro enterprise: Up to 10 workers and annual gross sales of up to eight million Dominican pesos (RD$ 8,000,000).
- Small enterprise: 11 to 50 workers and annual gross sales of up to fifty-four million Dominican pesos (RD$ 54,000,000).
- Medium enterprise: 51 to 150 workers and annual gross sales of up to two hundred and two million Dominican pesos (RD$ 202,000,000).
- Large enterprise: Over 150 workers and annual gross over (RD$ 202,000,000).
- Natural person: natural persons that are registered on the Registry of Providers of the Dominican Republic.
- Not classified: not classified business according to the Registry of Providers of the Dominican Republic.

# Example

```json
{
  "parties": [
    {
      "name": "Siemens, SRL",
      "id": "DO-RPE-12716",
      "identifier": {
        "scheme": "DO-RPE",
        "id": "12716",
        "legalName": "Siemens, SRL"
      },
      "roles": [
        "supplier"
      ],
      "address": {
        "streetAddress": "Avenida Pedro Henriquez Ureña No. 138, Torre Empresarial Reyna II, Piso 6 , 602, La Esperilla",
        "locality": "SANTO DOMINGO DE GUZMAN",
        "region": "DISTRITO NACIONAL"
      },
      "details": {
        "gender": "male",
        "scale": "large"
      }
    }  
  ]
}
```
