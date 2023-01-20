## Переход от старого руководства к новому или удаление Windows
> С помощью этого руководства, вы можете восстановть стандартную таблицу разделов для того, чтобы удалить Windows, или перейти от старого руководства к новому 

> Вам не нужно делать этот шаг, если вы не следовали старому руководству

# Восстановление стандартной таблицы разделов

Замените <gpt_both0.bin> на путь к файлу gpt_both0.bin, вы можете найти его на [странице релизов](../../../../releases/tag/binaries)

```cmd
fastboot flash partition:0 <gpt_both0.bin>
```

# Очистка userdata, чтобы избежать bootloop и восстановить размер файловой системы
```cmd
fastboot -w
```

## [Следующий шаг: Разметка](/guide/Russian/1-partitions-ru.md)