## Увага

Використано фічу New set methods: https://github.com/tc39/proposal-set-methods

P.S. Виконавши функцію shim() можна викликати методи (union, difference тощо) прямо у об'єктів Set,
але функція shim() чомусь працює лише у CommonJS, тобто якщо підключити пакет за допомогою require, 
в React це, мабуть, є можливим лише з Webpack.