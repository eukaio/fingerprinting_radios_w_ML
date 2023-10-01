# fingerprinting radios with machine learning

Research developed as the final paper of the Electronic and Telecommunications Engineering course.

The train and test data can be downloaded <a href="https://drive.google.com/file/d/1ihJGTQKijWHU47GBvjYqOa7XrU0ruudI/view?usp=sharing">here</a>.

The paper can be seen <a href="https://repositorio.ufu.br/handle/123456789/38403">here</a>.

----------------------------------------------------------------------

# Abstract
Electronic wireless devices cause unique physics variations in the emitting signals that can be used as a signature or a fingerprint. These variations can be interpreted as noise introduced by the electronic components of the transmitter into the signal. Due to subtle variations in the manufacturing process, no component is identical to another.

To conduct the study, signals emitted by low-cost wireless communication devices were collected using a Software-Defined Radio (SDR) equipment. These signals were processed to create a database that was used for training and validation of a Convolutional Neural Network (CNN). The developed CNN demonstrated a 98% accuracy in device identification using only the signals emitted by them.

The proposed technology operates passively and can be implemented in the control and gateway elements of a data network for device authentication. There is no need to modify the programming of the other network edge elements, which often suffer from severe hardware limitations.

Convolutional neural networks have proven to be a powerful and promising tool with the ability to identify unique patterns in radiofrequency signals and unequivocally differentiate one device from another.

----------------------------------------------------------------------

# Resumo
Dispositivos eletrônicos de transmissão sem fio imprimem variações físicas únicas nos sinais que emitem, as quais podem ser utilizadas como uma assinatura ou impressão digital do dispositivo emissor. Essas variações podem ser interpretadas como ruídos que os componentes eletrônicos do transmissor imprimem no sinal. Devido a sutis variações no processo de fabricação nenhum componente é idêntico a outro.

Para realizar o estudo, foram coletados sinais emitidos por dispositivos de comunicação sem fio de baixo custo, utilizando um equipamento de Rádio Definido por Software (SDR). Esses sinais foram processados para criar uma base de dados que foi utilizada no treinamento e validação de uma Rede Neural Convolucional (CNN). A CNN desenvolvida demonstrou uma acurácia de 98% na identificação dos dispositivos, utilizando apenas os sinais emitidos por eles.

A tecnologia proposta funciona de forma passiva, podendo ser implementada nos elementos de controle e de gateway de uma rede de dados para autenticação de dispositivos. Não é necessário alterar a programação dos demais elementos de borda da rede, que geralmente sofrem de severas limitações de hardware.

As redes neurais convolucionais provaram ser uma ferramenta poderosa e promissora, com capacidade de identificar padrões únicos em sinais de radiofrequência e diferenciar inequivocamente um dispositivo de outro.
