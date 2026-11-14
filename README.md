🚗 Fatura+

Analisador inteligente de ofertas de corridas para motoristas de aplicativo.

O Fatura+ é um aplicativo Android desenvolvido para auxiliar motoristas de transporte por aplicativo na avaliação de ofertas de corridas em tempo real.

Através da leitura das informações exibidas na tela, o aplicativo identifica os dados de uma oferta e apresenta indicadores que ajudam o motorista a avaliar sua rentabilidade antes de aceitar uma corrida.

O objetivo é transformar informações dispersas em indicadores simples, objetivos e de fácil interpretação.

✨ Funcionalidades

Leitura automática de ofertas: identificação das informações disponíveis nos cards de ofertas dos aplicativos Uber e 99.

Valor por quilômetro (R$/KM): cálculo da remuneração em relação à distância da corrida.

Ganho por hora (R$/H): estimativa de rendimento por hora, considerando os dados da oferta.

Avaliação do passageiro: identificação da nota apresentada no card da oferta.

Indicador visual de rentabilidade: classificação das ofertas por meio de uma barra colorida.

Interface flutuante: exibição das informações sobrepostas à tela do aplicativo de transporte.

Configurações personalizáveis: possibilidade de ajustar os parâmetros utilizados na avaliação das ofertas.

🎨 Sistema de classificação

O Fatura+ utiliza um sistema visual para facilitar a interpretação dos resultados:

Indicador

Significado

🟢 Verde

Oferta dentro dos parâmetros considerados vantajosos.

🟡 Amarelo

Oferta intermediária, que merece atenção.

🔴 Vermelho

Oferta abaixo dos parâmetros estabelecidos.

Os critérios de classificação podem ser ajustados conforme as necessidades e estratégias de cada motorista.

📱 Compatibilidade

O projeto foi desenvolvido para dispositivos Android e possui integração com os seguintes aplicativos:

Uber Driver

99 Motorista

A leitura das informações depende da disponibilidade e da estrutura visual dos cards apresentados pelos aplicativos de transporte.

🛠️ Tecnologias utilizadas

O Fatura+ utiliza tecnologias nativas do ecossistema Android:

Kotlin: linguagem principal de desenvolvimento.

Android SDK: recursos e APIs nativas do sistema operacional.

Accessibility Service: acesso aos elementos de interface necessários para identificar as informações exibidas na tela.

Google ML Kit: recursos de reconhecimento e processamento de texto (OCR).

Floating Overlay: interface flutuante para apresentação dos resultados durante o uso de outros aplicativos.

⚙️ Como funciona

O funcionamento do aplicativo pode ser dividido em quatro etapas:

Captura das informações: o serviço de acessibilidade identifica os elementos disponíveis na interface do aplicativo de transporte.

Reconhecimento dos dados: as informações relevantes são identificadas e processadas, utilizando os recursos disponíveis de leitura de texto.

Processamento matemático: os dados da oferta são utilizados para calcular os indicadores de rentabilidade.

Apresentação dos resultados: uma interface flutuante apresenta os indicadores e a classificação visual da oferta.

🔐 Permissões

Para funcionar corretamente, o Fatura+ necessita de permissões específicas do Android.

Acessibilidade: necessária para identificar informações exibidas na interface dos aplicativos compatíveis.

Sobreposição de tela: necessária para apresentar os indicadores por meio da interface flutuante.

Essas permissões devem ser concedidas manualmente pelo usuário nas configurações do Android.

🎯 Objetivo do projeto

O Fatura+ surgiu da necessidade de desenvolver uma ferramenta prática para auxiliar motoristas de aplicativo na tomada de decisões.

A proposta é oferecer uma leitura rápida da rentabilidade de cada corrida, permitindo que o motorista tenha mais informações para administrar seu tempo, distância percorrida e ganhos.

O projeto também representa um estudo prático sobre desenvolvimento Android, automação de interfaces, acessibilidade e reconhecimento de texto.

🚧 Status do projeto

Em desenvolvimento.

Novas funcionalidades, melhorias na identificação das ofertas e otimizações de desempenho poderão ser incorporadas ao longo da evolução do projeto.

⚠️ Aviso legal

O Fatura+ é um projeto independente, desenvolvido para fins de estudo e uso pessoal.

Não possui vínculo, parceria ou associação oficial com Uber Technologies Inc. ou 99 Tecnologia Ltda.

Uber e 99 são marcas de seus respectivos proprietários.

O aplicativo não realiza corridas, não aceita ofertas automaticamente e não modifica os aplicativos de transporte.

Fatura+ — Mais informação para decisões melhores.
