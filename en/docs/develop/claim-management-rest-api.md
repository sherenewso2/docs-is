---
template: templates/swagger.html
---

# Claim Management API Definition - v1

??? note "Click for instructions"
    Follow the instructions given below to try out the REST APIs with your local instance of WSO2 Identity Server. 
    
    1.  Click **Authorize** and provide the desired values for authentication. 
    2.  Expand the relevant API operation and click **Try It Out**.  
    3.  Fill in relevant sample values for the input parameters and click **Execute**. 
        You will receive a sample curl command with the sample values you filled in. 
    4. Add a `-k` header to the curl command and run the curl command on the terminal with a running instance of WSO2
     IS. 
    
<div id="swagger-ui"></div>
<script>
window.onload = function() {
  // Begin Swagger UI call region
  const ui = SwaggerUIBundle({
    url: "https://raw.githubusercontent.com/wso2/identity-api-server/v1.0.190/components/org.wso2.carbon.identity.api.server.claim.management/org.wso2.carbon.identity.rest.api.server.claim.management.v1/src/main/resources/claim-management.yaml",
    dom_id: '#swagger-ui',
    deepLinking: true,
    validatorUrl: null,
    presets: [
      SwaggerUIBundle.presets.apis,
      SwaggerUIStandalonePreset
    ],
    plugins: [
      SwaggerUIBundle.plugins.DownloadUrl
    ],
    layout: "StandaloneLayout"
  })
  // End Swagger UI call region

  window.ui = ui
}
</script>

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/4bc7377da85b9dcd0516).