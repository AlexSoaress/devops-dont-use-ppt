# DevOps: O equilíbrio quase perfeito entre código, infra e café frio

![image](https://github.com/user-attachments/assets/0a784376-bd68-4d0f-a428-26ce0045d2b9)

### O que vamos explorar?
- O que é DevOps e por que ele surgiu?
- Os problemas do modelo tradicional e como o DevOps resolve esses desafios.
- Como a cultura DevOps promove colaboração, transparência e responsabilidade compartilhada.
- A importância da automação para acelerar entregas e reduzir falhas.

### O que é DevOps?    
<div align="left">
  <img src="https://github.com/user-attachments/assets/3677693a-7fc2-434f-984d-78abad76ddf5" width="580px">
</div> 

O termo DevOps surgiu por volta de 2007, quando engenheiros perceberam que o modelo tradicional de desenvolvimento de software estava ineficiente e cheio de falhas. 
### Como funcionava antes?

- Desenvolvedores criavam o código e passavam para a equipe de operações.
- A equipe de operações (Ops) implantava e mantinha o software funcionando.
- O problema? As metas eram completamente opostas.
  
**Meta dos devs:** Entregar novas features rapidamente.  
**Meta do time de ops:** Manter o sistema estável o máximo possível.

Como sistemas geralmente quebram devido a mudanças, essas metas entravam em conflito constante.
<div align="left">
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExMDl5Y3M2M3VwYjY2eWtpcW92amwzaDFvMGlhY2VkZ3lqbjJsNGg4ZSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oriNW27pn33u8rtuw/giphy.gif" width="580px">
</div>

E assim que surgiu o termo "muro da confusão", separando desenvolvimento e operações, desevoldores jogavam patchs de codigo por cima do muro para implantacao e o time de ops devolvia erros e metricas de dowtime.  

## Antes vs. Depois do DevOps  

<div align="left">
  <img src="https://github.com/user-attachments/assets/6956fa1f-d42c-40bd-b7d3-b1cfd3572be2" width="700px">
</div>  

| Antes do DevOps | Com o DevOps |
|-----------------|-------------|
|  **Processos manuais e demorados** → Publicações levavam dias ou semanas. |  **Entrega contínua** → Atualizações frequentes e seguras. |
|  **Falta de colaboração** → Devs e Ops trabalhavam separados. |  **Cultura de responsabilidade compartilhada** → Todos engajados no ciclo de vida do software. |
|  **Erros frequentes e demora na solução** → Testes manuais aumentavam falhas. |  **Automação e velocidade** → Reduz o trabalho manual e acelera processos. |
|  **Dificuldade de escalabilidade** → Infraestrutura exigia muito tempo e esforço. |  **Escalabilidade facilitada** → Infraestrutura se ajusta rapidamente conforme a demanda. |\

## Automação de Processos  

Automatizar tarefas repetitivas é um dos principais objetivos do **DevOps**. Isso reduz erros humanos, melhora a eficiência e libera tempo para tarefas estratégicas.  

<div align="left">
  <img src="https://github.com/user-attachments/assets/af874207-c42a-4f5b-97a5-6c0068e64811" width="700px">
</div>  

### **Principais áreas de automação**  

| Processo | O que faz? |
|------------|-------------|
| **Integração Contínua (CI)** | Automatiza testes para garantir que cada alteração no código funcione corretamente. Identifica erros antes de chegar à produção. |
| **Entrega Contínua (CD)** | Publicação automática do software para ambientes de teste e produção, garantindo que novas funcionalidades cheguem mais rápido aos usuários. |
| **Infraestrutura como Código (IaC)** | Criação e configuração automática de servidores, redes e outros recursos. |
| **Monitoramento e Resolução** | Disparo automático de alertas, reinício de serviços e monitoramento contínuo para evitar falhas antes que impactem os usuários. |

## "You Build It, You Run It" – Você constrói, você mantém!  

<div align="left">
  <img src="https://github.com/user-attachments/assets/cdcdd980-7d3e-4ab1-8f76-1712a0298c62" width="500px">
</div>  

No **DevOps**, quem desenvolve também ajuda a manter o código funcionando.  

- Isso torna os sistemas mais **estáveis e confiáveis**.  
- Popularizado por **Werner Vogels (CTO da Amazon)**.  
- Adotado por **Amazon, Netflix e Google** para garantir entregas ágeis e seguras.

## DevOps é mais do que tecnologia, é uma mudança de cultura!  

<div align="left">
  <img src="https://i.gifer.com/P9JD.gif" width="500px">
</div>  

O verdadeiro impacto do **DevOps** está na forma como as equipes **colaboram**. Mais do que ferramentas e automação, ele traz uma nova mentalidade de trabalho:  

**Equipes trabalhando juntas em todas as etapas do desenvolvimento.**  
**Mais alinhamento, transparência e eficiência.**  
**Responsabilidade compartilhada: problemas e melhorias são um esforço coletivo.**  

Indicações literárias:  
[Manual de DevOps: Como Obter Agilidade, Confiabilidade e Segurança em Organizações Tecnológicas](https://www.amazon.com.br/Manual-DevOps-confiabilidade-organiza%C3%A7%C3%B5es-tecnol%C3%B3gicas/dp/8550802697/ref=sr_1_2?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=ZU369KL6JU2O&dib=eyJ2IjoiMSJ9.5HhR159FD3N410wnkvM5ZuBSVWzaLy2O_kDp-YExFTXPCR5BYpoCzrwwZa-LvCnLuyDmGWXDJsGYhnhikw9o2HOav3j4XTh00_FbBjLw698xtd4CcHkxWIr78CHuoe2z-8lAlOPWbTV7_4KfXt-pnJ5IRhHO1Pp3YZSzvkB1_UYsXk9HXcKCrXqELr5nWvr4-i1UnrqiwDj6oS5Wl4YZEdXtCF1CdnK47pxmKDyMX2YpB9eJku5vO7uQLnMHa6Sgr2tB55jwav2J25atyklVDvsLKrLuB2DhxeswKwU9oDqfZLhNEvY8lb6RoOzKgWWM4Qrge4BODNyp_P2t0wTm5GyIaGEygQqplD8yBd-riDBjlmOh59Gt99duBe4OsHwLc575oHRAXPMeAvbfnkRR0O7CZGYuKh7rtataNXqCuE4ZhCpmkXeoUKEzbhWzxH-4.uFztnl_TTtgH-Ml4F6Z0mXpSH-som3SKDP1AV1PCrMA&dib_tag=se&keywords=devops&qid=1742416570&sprefix=devop%2Caps%2C216&sr=8-2&ufe=app_do%3Aamzn1.fos.6d798eae-cadf-45de-946a-f477d47705b9)  
[O Projeto Fênix – Edição Comemorativa: um Romance Sobre TI, DevOps e Sobre Ajudar o seu Negócio a Vencer](https://www.amazon.com.br/Projeto-F%C3%AAnix-Comemorativa-Romance-Neg%C3%B3cio/dp/8550814067/ref=sr_1_1?crid=UC46QARR34ZD&dib=eyJ2IjoiMSJ9.zjpPcCb7nUVUevIweBIs3nvzNpHaCkIDT_fdaBfWhdkzLDlRTj-LjMMan2UFd5bOoxfwENmOZhgvqun8PXJM4uv98pf_BblxalFXeBNBioe2kMD5TAZ2cdXhaDgCvg1MxhTIY-_AaNZYIr8mtFX594TBzRKLbNNkkJMD5UFyb6wLGSMCTWxfUtxXzEXdw8SAswwH84h17j6KkBXfKdvB2agJeHm1E5MJZl-vWIok90e3hAbH4LXdzGCUj3cYUbFN.cu-Fae1TQzswyfRG1b20UyNMh3uefeSYTjNhcxF8mFM&dib_tag=se&keywords=projeto+fenix&qid=1742416815&sprefix=projeto+feni%2Caps%2C237&sr=8-1&ufe=app_do%3Aamzn1.fos.6d798eae-cadf-45de-946a-f477d47705b9)  
[Engenharia de Confiabilidade do Google: Como o Google Administra Seus Sistemas de Produção](https://www.amazon.com.br/Engenharia-Confiabilidade-Google-Administra-Sistemas/dp/8575225170/ref=sr_1_1?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dib=eyJ2IjoiMSJ9.hFLYWz71nucJQRshsyyTGaG4STRboLLSHetceGsbHp5V-b2b1Ta0zTQjo2o0xoCz6p2t7fU-0n5NUwC5WOxmY8FHGoBoGTQvDmFQYRf_GvWtz42gBOZLoCDNtEeT0z6JxT8b4M94vEKZh7cWhLVAYw.PulDpQG97fUP84MWoApnP3wDbLJ1YyMsvc3O-Ib5B0w&dib_tag=se&keywords=sre+google&qid=1742416891&sr=8-1&ufe=app_do%3Aamzn1.fos.6d798eae-cadf-45de-946a-f477d47705b9)  
[Código Limpo: Habilidades Práticas do Agile Software](https://www.amazon.com.br/C%C3%B3digo-limpo-Robert-C-Martin/dp/8576082675/ref=sr_1_1?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=35O9997FAT56C&dib=eyJ2IjoiMSJ9.jhdpaoLexCD3caZwL14EnrRn0EhpQADyEw-yog_G_MH-7OeQk8mwsnxP89fN_rqsi09Pz5hJTxkeqYHhJ84XzYaZxC8oWTdWapAX_gs49oRrerUmdvh8G9omLEBjaJwCk6y7uwcgHOrSNM4KhMlPdY13OnKBd56YILIR5rDjKQxEVFp67cCFuuFyVv-CztnBkJ-IZv3DYtEJG5dioXVmE0rqvW5ykGjARICN0L8JyKrQU0kzbPD2N-1ivKvVVdjR7fQgl-MnGEGsFYQpX-onPXlPB-vkxFWTHxymQgnEYqhPrdg1fA7wziPZ_sHvBif2SutbX3oCLE69GIsUTNklcwWr-vFd-yFacDFDncJ285do2xztDSuLRwwD3S6ClGPVgkrLJsgPHhtdJ3eQxO_QZNL1fq9DdgnOba0pd7-Ashn3CruZGYvib77_BhQLOGBC.TJZxW6upQniWqufqE8NCYnAv168N7RKsqLYloXt6gbo&dib_tag=se&keywords=clean+code&qid=1742416956&sprefix=clean+code%2Caps%2C215&sr=8-1&ufe=app_do%3Aamzn1.fos.6d798eae-cadf-45de-946a-f477d47705b9)



















 
  







