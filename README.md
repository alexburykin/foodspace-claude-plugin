# Foodspace для Claude

Маркетплейс з одним плагіном, `foodspace`. Плагін підключає Claude до
[Foodspace](https://food.leburykina.com), сімейного щоденника їжі та книги
рецептів: записувати зʼїдене за фото й текстом, зберігати етикетки та
рецепти, дивитись КБЖУ дня і свій дашборд прямо в чаті.

Усередині лише конектор MCP (`https://food.leburykina.com/api/mcp`) і скіл
`foodspace-diary`. Секретів у репозиторії нема: доступ до щоденника дає вхід
у Foodspace і твоя згода.

## Встановлення в claude.ai або Claude Desktop

1. Customize → Plugins → Add → **Add marketplace**.
2. Введи `alexburykin/foodspace-claude-plugin`.
3. У списку плагінів вибери **Foodspace** → Add.
4. Відкрий плагін → вкладка **Connectors** → Foodspace → **Connect**.
5. Увійди у Foodspace через Google або логіном і паролем і натисни
   «Дозволити».

Після цього плагін доступний і в мобільному Claude. Нові версії приходять
самі.

## Встановлення в Claude Code

```bash
claude plugin marketplace add alexburykin/foodspace-claude-plugin
claude plugin install foodspace@burykin-foodspace
```

## Відкликати доступ

На сторінці https://food.leburykina.com/connect, блок «Підключення».
