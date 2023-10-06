# Kubernetes Simulator

Este projeto é uma simulação simples de um cluster Kubernetes usando threads em Python. Ele inclui um nodo Master, nodos Workers e a alocação de PODs com base em capacidades de CPU, memória e disco.

## Funcionalidades

- **PODs**: Representam as unidades de trabalho a serem executadas nos Workers. Cada POD possui atributos como CPU, memória e espaço em disco, simulando diferentes requisitos computacionais.

- **Workers**: São os nodos do cluster Kubernetes. Eles possuem capacidades específicas de CPU, memória, latência de rede e espaço em disco. Os Workers processam tarefas simuladas e alocam PODs com base em suas capacidades.

- **Master**: Coordena a alocação de PODs nos Workers. Ele aguarda a chegada de PODs na fila e tenta alocá-los nos Workers disponíveis.

- **Producer**: Simula a produção contínua de PODs. Cada POD é gerado com capacidades variadas de CPU, memória e disco.

- **Processamento Contínuo**: Os Workers simulam o processamento contínuo de tarefas e a liberação de recursos quando os PODs são concluídos.

- **Alocação Dinâmica**: O sistema aloca dinamicamente PODs nos Workers com base nas capacidades disponíveis, tentando otimizar o uso de recursos.

## Requisitos

- Python 3.x






