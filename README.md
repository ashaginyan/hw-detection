# hw-detection

## Как все делалось

Был подготовлен yaml для датасета (```configs/data_configs/data_config```), гиперпараметры обучения использовались стандартные. В ```configs/experiments/``` лежат конфиги экспериментов. Трекинг осуществлялся в ClearML (автоподключение логов ultralytics к ClearML). Детекция осуществлялась на 1 класс: ```face```.

## Эксперименты

Тестово были запущены три модели на 10 эпох: yolov5n, yolov5m, yolov8m. Все три результата оставляют желать лучшего. Предположительно: проблемы с разметкой в исходных данных.

## Результаты

```YOLOv5n```: https://app.clear.ml/projects/2681fe0c782444ddbfd39577930cfe17/experiments/d9369774017a470f89e260ef8ac3e73b/output/execution

```YOLOv5m```: https://app.clear.ml/projects/2681fe0c782444ddbfd39577930cfe17/experiments/81458a75cdca49c8bca098492ebd4094/output/execution

```YOLOv8m```: https://app.clear.ml/projects/2681fe0c782444ddbfd39577930cfe17/experiments/c0154a20ef9140d083daa8fba7f0b7b4/output/execution
