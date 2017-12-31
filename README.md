# Chatkit

## Design

### Adapter

Slack , Telegram ..... => Unified to Chatkit's message structure .

### Filter

The chatkit will run every registered fliters . If the filter is agreed , it will run their handlers .

### Handler

One filter has N handlers .

### Plugins

You can write your plugin which implemented a `filter` or a `handler` to offer some ability for other developers . 
