# Подготовка переменных (RX CheckVariables Component)

#### Описание:

Проверка всех нужных для остальных компонентов переменных и директорий.

#### Логика:

Проверяет наличие переменных: $[RXVERSION](https://git.starkovgrp.ru/ci-cd-components/Completed-RXDTDeploy-Component#rxversion), $[DDSFolderPath](https://git.starkovgrp.ru/ci-cd-components/Completed-RXDTDeploy-Component#ddsfolderpath), $[DTFolderPath](https://git.starkovgrp.ru/ci-cd-components/Completed-RXDTDeploy-Component#dtfolderpath), $[ProjectsFolderPath](https://git.starkovgrp.ru/ci-cd-components/Completed-RXDTDeploy-Component#projectsfolderpath)  
Проверяет наличие директорий: \$[DDSFolderPath](https://git.starkovgrp.ru/ci-cd-components/Completed-RXDTDeploy-Component/-/tree/main?ref_type=heads#ddsfolderpath)/\$[RXVERSION](https://git.starkovgrp.ru/ci-cd-components/Completed-RXDTDeploy-Component/-/tree/main?ref_type=heads#rxversion), \$[DTFolderPath](https://git.starkovgrp.ru/ci-cd-components/Completed-RXDTDeploy-Component/-/tree/main?ref_type=heads#dtfolderpath)/\$[RXVERSION](https://git.starkovgrp.ru/ci-cd-components/Completed-RXDTDeploy-Component/-/tree/main?ref_type=heads#rxversion)  
Проверяет наличие переменных с префиксом $[DeployDestination](https://git.starkovgrp.ru/ci-cd-components/Completed-RXDTDeploy-Component/-/tree/main?ref_type=heads#deploydestination), если он указан