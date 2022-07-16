# DsMeta

This is a full stack project developed @ "Semana Spring React" promoted by Devsuperior. It sends notifications to the seller phone number with the informations about the sales.

## Tech Stack

**Client:** React, TypeScript, Axios, React-tostify, React-datepicker, Vite

**Server:** Java 17, Spring, SQL, Twilio


## Link
https://david-dsmeta.netlify.app

## API Reference

#### Get sales

```http
  GET https://david-dsmeta.herokuapp.com/sales?minDate=2022-01-01&maxDate=2022-03-31
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `minDate` | `string` | **Required** |
| `maxDate` | `string` | **Required**. |

#### Get item

```http
  GET https://david-dsmeta.herokuapp.com/sales/${id}/notification
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |


## Preview

![](project-img.jpg)

## Author

- [David Nunes](https://www.github.com/Dnuns)
