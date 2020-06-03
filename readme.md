# Integração Epbx Manager x SalesForce

# 1 - Configurar arquivo callcenter.xml

```xml
  <callCenter>
   <section sortOrder="0" name="reqGeneralInfo" label="General Information">
    <item sortOrder="0" name="reqInternalName" label="InternalName">EpbxManagerAdapter</item>
    <item sortOrder="1" name="reqDisplayName" label="Display Name">EpbxManager Call Center Adapter</item>
    <item sortOrder="2" name="reqAdapterUrl" label="CTI Adapter URL">https://domain:port/softphone</item>
    <item sortOrder="3" name="reqUseApi" label="Use CTI API">true</item>
    <item sortOrder="4" name="reqSoftphoneHeight" label="Softphone Height">300</item>
    <item sortOrder="5" name="reqSoftphoneWidth" label="Softphone Width">500</item>
    <item sortOrder="6" name="reqSalesforceCompatabilityMode" label=" Salesforce Compatibility Mode">Classic</item>
   </section>
   <section sortOrder="1" name="reqDialingOptions" label="Dialing Options">
    <item sortOrder="0" name="reqOutsidePrefix" label="Outside Prefix">9</item>
    <item sortOrder="1" name="reqLongDistPrefix" label="Long Distance Prefix">1</item>
    <item sortOrder="2" name="reqInternationalPrefix" label="International Prefix">01</item>
   </section>
</callCenter>
```


# 2 - Criar página de integração no VisualForce Pages
# copie todo o conteudo do arquivo atendimento.html e cole na criação da página
![alt text](https://github.com/talktelecom/salesforce/blob/master/images/VisualForcePage.JPG)


# 3 - Apos criar a página precisamos configurar o Callcenter com a URL do Visualforce Pages
# Acesse o menu callcenter e altere o campo reqAdapterUrl com a URl da página do Visualforce page  
![alt text](https://github.com/talktelecom/salesforce/blob/master/images/Callcenter1.JPG)


# 5 - Criar App 
# Acesse o menu setup e depois clique em Add App
![alt text](https://github.com/talktelecom/salesforce/blob/master/images/App1.JPG)

# Crie um novo App e selecione a opção console
![alt text](https://github.com/talktelecom/salesforce/blob/master/images/App2.JPG)

# Informe o nome do App
![alt text](https://github.com/talktelecom/salesforce/blob/master/images/App3.JPG)

# Selecione o item cases
![alt text](https://github.com/talktelecom/salesforce/blob/master/images/App4.JPG)

# Avançar
![alt text](https://github.com/talktelecom/salesforce/blob/master/images/App5.JPG)

# Selecione a opção "As a primary tab"
![alt text](https://github.com/talktelecom/salesforce/blob/master/images/App5.JPG)

# Selecione todos
![alt text](https://github.com/talktelecom/salesforce/blob/master/images/App6.JPG)

# Selecione o App criado
![alt text](https://github.com/talktelecom/salesforce/blob/master/images/App7.JPG)

# Teste a integração
![alt text](https://github.com/talktelecom/salesforce/blob/master/images/App8.JPG)
