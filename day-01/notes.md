# Day 01

## Что изучил

Сегодня повторил базу по API и Postman.

Разобрал:
- что такое API и HTTP;
- из чего состоят request и response;
- что такое endpoint;
- HTTP методы GET, POST, PUT, PATCH, DELETE;
- path и query параметры;
- headers;
- body;
- JSON;
- основные status codes;
- что такое OpenAPI;
- что такое Swagger UI и чем он отличается от OpenAPI;
- основные части запроса и ответа в Postman.

## Что сделал руками

Работал со Swagger Petstore.

Через Swagger и Postman сделал полный CRUD:
- создал pet;
- получил pet по ID;
- изменил pet;
- проверил, что изменения сохранились;
- удалил pet;
- после удаления повторно сделал GET по тому же ID и получил 404 Not Found.

В Postman разобрал вкладки:
- Params;
- Authorization;
- Headers;
- Body;
- Scripts;
- Response.

Попробовал первый автоматический тест в After response:

pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});

Специально запустил его для уже удалённого pet. Ожидал 200, фактически API вернул 404, поэтому тест корректно упал с FAILED.

## Что пока надо повторить

Пока не очень уверенно чувствую себя с:
- Before request scripts;
- After response scripts;
- автоматическими проверками в Postman;
- JavaScript внутри Postman.

К этим темам надо возвращаться дальше на практике.

## Дополнительно

Обновили учебный план и связали его с моими курсами Udemy. Теперь в задачах будут конкретные темы курса, практика, README и commit.