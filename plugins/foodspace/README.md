# Foodspace для Claude

Плагін підключає Claude до Foodspace, сімейного щоденника їжі та книги
рецептів Бурикіних. Усередині скіл `foodspace-diary` (як працювати з фото
тарілки, етикеткою, текстом рецепта чи підсумками дня) і конектор MCP
`https://food.leburykina.com/api/mcp`.

## Встановлення

1. Claude: Customize → Plugins → Add → Add marketplace →
   `alexburykin/foodspace-claude-plugin`, потім Foodspace → Add. Або
   Upload plugin і `foodspace-plugin.zip` зі сторінки
   https://food.leburykina.com/connect.
2. Вкладка Connectors → Foodspace → Connect.
3. Відкриється Foodspace: увійди через Google або логіном і паролем і
   натисни «Дозволити». Секретів у плагіні нема, доступ дає лише твоя згода.

## Що вміє

- Записувати з'їдене за фото, вагою чи текстом, з прев'ю перед збереженням.
- Зберігати етикетки продуктів і домашні рецепти, спільні для сім'ї.
- Показувати день, тиждень і дашборд, ставити цілі КБЖУ.

Відкликати доступ можна будь-коли на сторінці «Підключити AI» в Foodspace.
