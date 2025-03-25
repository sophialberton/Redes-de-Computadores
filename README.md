# Redes-de-Computadores
Aulas e revisão de redes de computadores
# Resumo dos Conceitos de Redes de Computadores

## 1. Princípios Básicos de Redes de Computadores
Redes de computadores são conjuntos de dispositivos interconectados que compartilham recursos e informações. Elas são essenciais para a comunicação eficiente entre sistemas, facilitando a troca de dados, colaboração em tempo real e acesso a recursos distribuídos. A evolução das redes começou na década de 1960 com a ARPANET, passando pelo desenvolvimento do TCP/IP, popularização da internet e avanços como Wi-Fi, IoT e redes 5G.

### Tipos de Redes:
- **LAN (Local Area Network)**: Conecta dispositivos em uma área limitada, como escritórios ou residências, com alta velocidade e baixa latência.
- **MAN (Metropolitan Area Network)**: Cobre áreas maiores, como cidades ou campus universitários, com velocidade e latência variáveis.
- **WAN (Wide Area Network)**: Interconecta redes em grandes distâncias, como entre países, com menor velocidade e maior latência.

### Topologias de Rede:
- **Estrela**: Dispositivos conectados a um central (ex: switch). Vantagem: fácil gerenciamento. Desvantagem: falha no central afeta toda a rede.
- **Barramento**: Todos conectados a um cabo central. Vantagem: simples e econômico. Desvantagem: congestionamento e colisões.
- **Anel**: Dispositivos em círculo. Vantagem: transmissão ordenada. Desvantagem: falha em um dispositivo interrompe a rede.
- **Malha**: Múltiplas conexões entre dispositivos. Vantagem: alta redundância. Desvantagem: complexa e cara.
- **Híbrida**: Combina duas ou mais topologias para flexibilidade.

---

## 2. Modelos de Referência: OSI e TCP/IP
Os modelos OSI e TCP/IP padronizam a comunicação entre dispositivos em redes.

### Modelo OSI (7 camadas):
1. **Aplicação**: Interface com aplicações (ex: HTTP, FTP).
2. **Apresentação**: Conversão de formatos e criptografia.
3. **Sessão**: Gerencia sessões de comunicação.
4. **Transporte**: Controle de fluxo e integridade (ex: TCP).
5. **Rede**: Endereçamento lógico e roteamento (ex: IP).
6. **Enlace**: Endereçamento físico e transmissão confiável (ex: Ethernet).
7. **Física**: Transmissão de bits por meios físicos.

### Modelo TCP/IP (4 camadas):
1. **Aplicação**: Combina as camadas 5, 6 e 7 do OSI.
2. **Transporte**: Similar à camada 4 do OSI.
3. **Rede**: Similar à camada 3 do OSI.
4. **Enlace/Física**: Combina as camadas 1 e 2 do OSI.

### Comparação:
- **OSI**: Teórico, educativo, mais flexível.
- **TCP/IP**: Prático, amplamente usado na internet.

---

## 3. Camada Física e Meios de Transmissão
A camada física converte bits em sinais físicos e utiliza meios guiados ou não guiados para transmissão.

### Meios Guiados:
- **Cabo coaxial**: Usado em TV e redes antigas.
- **Par trançado**: Econômico e comum (ex: UTP, STP).
- **Fibra óptica**: Alta velocidade e imunidade a interferências (ex: monomodo e multimodo).

### Meios Não Guiados:
- **Wi-Fi**: Redes locais sem fio.
- **Bluetooth**: Conexão curta distância.
- **ZigBee**: Baixo consumo, usado em IoT.

### Equipamentos de Rede:
- **Hub**: Repassa dados para todos os dispositivos (ineficiente).
- **Switch**: Encaminha dados apenas para o destinatário (eficiente).
- **Roteador**: Conecta redes diferentes (ex: internet).
- **Modem**: Converte sinais da operadora para a rede local.

---

## 4. Camada de Enlace de Dados
Responsável por enquadrar dados, controle de erros e fluxo, e endereçamento físico (MAC).

### Funções:
1. **Enquadramento**: Organiza bits em quadros (frames).
2. **Controle de Erros**: Detecta e corrige erros usando técnicas como:
   - **Paridade**: Adiciona bit para verificação.
   - **CRC (Cyclic Redundancy Check)**: Método robusto para detecção.
   - **Códigos de Hamming**: Correção de erros.
3. **Controle de Fluxo**: Evita sobrecarga do receptor (ex: protocolo Janela Deslizante).

### Protocolos:
- **Stop-and-Wait**: Envia um quadro e aguarda confirmação (lento).
- **Janela Deslizante**: Envia múltiplos quadros antes de aguardar confirmação (eficiente).

### Endereço MAC:
Identificador único de hardware usado para comunicação em redes locais.

---

## Conclusão
O estudo das redes de computadores abrange desde princípios básicos até detalhes técnicos de camadas e protocolos. Compreender esses conceitos é essencial para projetar, implementar e solucionar problemas em sistemas de comunicação modernos.
