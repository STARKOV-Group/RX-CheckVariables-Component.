# Подготовка переменных (RX CheckVariables Component)

#### Описание:

Проверка всех нужных для остальных компонентов переменных и директорий.

#### Логика:

Проверяет наличие переменных: $[RXVERSION](https://github.com/STARKOV-Group/Completed-RXDTDeploy-Component/#rxversion), $[DDSFolderPath](https://github.com/STARKOV-Group/Completed-RXDTDeploy-Component/#ddsfolderpath), $[DTFolderPath](https://github.com/STARKOV-Group/Completed-RXDTDeploy-Component/#dtfolderpath), $[ProjectsFolderPath](https://github.com/STARKOV-Group/Completed-RXDTDeploy-Component/#projectsfolderpath)  
Проверяет наличие директорий: \$[DDSFolderPath](https://github.com/STARKOV-Group/Completed-RXDTDeploy-Component/#ddsfolderpath)/\$[RXVERSION](https://github.com/STARKOV-Group/Completed-RXDTDeploy-Component/#rxversion), \$[DTFolderPath](https://github.com/STARKOV-Group/Completed-RXDTDeploy-Component/#dtfolderpath)/\$[RXVERSION](https://github.com/STARKOV-Group/Completed-RXDTDeploy-Component/#rxversion)  

Проверяет наличие переменных с префиксом $[DeployDestination](https://github.com/STARKOV-Group/Completed-RXDTDeploy-Component/#deploydestination), если он указан
