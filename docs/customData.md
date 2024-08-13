<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>Document with 15 Paragraphs</title> 
    <style> 
        body { 
            font-family: Arial, sans-serif; 
            background-color: #f4f4f4; 
            margin: 0; 
            padding: 0; 
        } 
        header { 
            background-color: #333; 
            color: white; 
            padding: 1em; 
            text-align: center; 
        } 
        main { 
            padding: 1em; 
        } 
        .container { 
            max-width: 800px; 
            margin: 0 auto; 
            background-color: white; 
            padding: 2em; 
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); 
        } 
        footer { 
            background-color: #333; 
            color: white; 
            text-align: center; 
            padding: 1em; 
            position: fixed; 
            width: 100%; 
            bottom: 0; 
        } 
        a { 
            color: #0066cc; 
            text-decoration: none; 
        } 
        a:hover { 
            text-decoration: underline; 
        } 
    </style> 
</head> 
<body> 
    <header> 
        <h1>Համահայկական գրողների միություն</h1> 
    </header> 
    <main> 
        <div class="container"> 
            <h2>Մեր մասին</h2> 
            <p> Համահայկական գրողների միությունը կազմակերպություն է, որը հիմնադրվել է 2011 թ․ Երևանում, ունի մեծագույն փորձ գրական կապերի հաստատման և ստեղծագործական իրականության իրականացման ասպարեզում։ Ունի մասնաճյուղեր Մինսկում, Համբուրգում և Օսթինում /Տեխաս/, գլխավոր գրասենյակը գտնվում է Երևանում։ </p> 
            <h2>Մեր անդամները </h2> 
            <p>Աբգար Ափինյան – /05․02․1960 – / գրականագետ, ՀՀԳՄ նախագահ, "Հայրենիքի ձայն" թերթի խմբագրական խորհրդի նախագահ</h2>
            <p>Սուսաննա Ղազարյան – /04․07․1984 – / բանաստեղծուհի, ՀՀԳՄ փոխնախագահ, "Հայրենիքի ձայն" թերթի գլխավոր խմբագիր</h2> 
            <p>Աբել Սևունց – /11.06.2009 – /  բանաստեղծ, դաշնակահար</h2>
            <p>Սարգիս Հայենց – /14.02.2003 – / բանաստեղծ, երգիչ</h2> 
            <h2>"Հայրենիքի ձայն" ամսաթերթ</h2> 
            <p>Այստեղ տեղադրված կլինեն "Հայրենիքի ձայն" ամսաթերթի էլեկտրոնային տարբերակները և նորություններ ամսաթերթի վերաբերյալ.</p> 
            <h2>"Սփյուռք" ամսաթերթ</h2> 
            <h2>Այստեղ տեղադրված կլինեն "Սփյուռք" ամսաթերթի էլեկտրոնային տարբերակները և նորություններ ամսաթերթի վերաբերյալ </p> 
            <h2>"Նոր դար" հեռուստահաղորդաշար</h2> 
            <h2>Այստեղ տեղադրված կլինեն "Նոր դար" հեռուստահաղորդաշարի թողարկումները և անոնսները։ Հաղորդաշարը ցուցադրվում է ամեն կիրակի 19։50–ին, Ա ԹԻՎԻ–ով</p> 
            <h2>"Նոր դար" ամսագիր</p>
            <p>Այստեղ տեղադրված կլինեն "Նոր դար" ամսագրի էլեկտրոնային տարբերակները և նորություններ ամսագրի վերաբերյալ</h2> 
            <p></h2>
            <p>Paragraph content for section 6.</p> 
            <h2>Section 7</h2> 
            <p>Paragraph content for section 7.</p> 
            <h2>Section 8</h2> 
            <p>Paragraph content for section 8.</p> 
            <h2>Section 9</h2> 
            <p>Paragraph content for section 9.</p> 
            <h2>Section 10</h2> 
            <p>Paragraph content for section 10.</p> 
            <h2>Section 11</h2> 
            <p>Paragraph content for section 11.</p> 
            <h2>Section 12</h2> 
            <p>Paragraph content for section 12.</p> 
            <h2>Section 13</h2> 
            <p>Paragraph content for section 13.</p> 
            <h2>Section 14</h2> 
            <p>Paragraph content for section 14.</p> 
            <h2>Section 15</h2> 
            <p>Paragraph content for section 15.</p> 
        </div> 
        <div class="container"> 
            <h2>Additional Information</h2> 
            <p>For more information, visit <a href="https://www.example.com">this link</a>.</p> 
        </div> 
    </main> 
    <footer> 
        <p>&copy; 2024 My Website</p> 
    </footer> 
</body> 
</html>

      "name": "foo",
      "description": "The foo element",
      "attributes": [
        { "name": "bar" },
        {
          "name": "baz",
          "values": [
            {
              "name": "baz-val-1"
            }
          ]
        }
      ]
    }
  ],
  "globalAttributes": [
    { "name": "fooAttr", "description": "Foo Attribute" },
    { "name": "xattr", "description": "X attributes", "valueSet": "x" }
  ],
  "valueSets": [
    {
      "name": "x",
      "values": [
        {
          "name": "xval",
          "description": "x value"
        }
      ]
    }
  ]
}
```

- Completion on `<|` will provide `foo`
- Completion on `<foo |` will provide `bar` and `baz`
- Completion on `<foo baz=|` will provide `baz-val-1`
- Completion on `<foo |` will also provide the global attributes `fooAttr` and `xattr`
- Completion on `<foo xattr=>` will provide all values in valueSet `x`, which is `xval`
- Hover on `foo` will show `The foo element`

### Additional properties

For either `tag`, `attribute` or `attributeValue`, you can provide a `references` property of the following form

```json
{
  "tags": [
    {
      "name": "foo",
      "description": "The foo element",
      "references": [
        {
          "name": "My foo element reference",
          "url": "https://www.foo.com/element/foo"
        }
      ]
    }
  ]
}
```

It will be displayed in Markdown form in completion and hover as `[My foo element reference](https://www.foo.com/element/foo)`.
