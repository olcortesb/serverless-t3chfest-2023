# serverless-t3chfest-2023
Notas, apuntes y referencias de la charla Serverless y sus condimentos. (2 Marzo 2023)

## Por que de la charla:
- Ley de la tricotomía: https://es.wikipedia.org/wiki/Ley_de_tricotom%C3%ADa

## Condimentos:
- El cuento de la Isla desconocida (José Saramago): https://www.uv.mx/blogs/lectores/files/2012/11/el-cuento-de-la-isla-desconocida.pdf
- Google Trends: https://trends.google.es/trends/explore?date=all&q=serverless
- Serverless Framework:
  Herramienta de infraestructura como codigo(IaC), fue una de las primeras en aparecer par serverless espesificamente.
    - https://www.serverless.com/
- Serverless in 2012: https://readwrite.com/why-the-future-of-software-and-apps-is-serverless/ 


### Limites

#### Ejemplo limites de `payload``
- Apache: https://httpd.apache.org/docs/2.4/mod/core.html#limitrequestbody
- AWS Lambda: https://docs.aws.amazon.com/lambda/latest/dg/gettingstarted-limits.html
- Azure Functions: https://learn.microsoft.com/en-us/azure/azure-functions/functions-scale
- Google Cloud Functions: https://cloud.google.com/functions/quotas?hl=es-419
- CloudFlare Workers: https://developers.cloudflare.com/workers/platform/limits/#:~:text=%E2%80%8B%E2%80%8B%20Worker%20size,project%20goals%20by%20contacting%20Cloudflare.

#### Como resolver limite de 6 megas de AWS Lambda:
- https://theburningmonk.com/2020/04/hit-the-6mb-lambda-payload-limit-heres-what-you-can-do/

### Diseño
- Articulo diseño toyota/Aws: https://aws.amazon.com/es/blogs/architecture/toyota-connected-and-aws-design-and-deliver-collision-assistance-application/

#### Tamaños:
- Lambda layers: https://docs.aws.amazon.com/lambda/latest/dg/configuration-layers.html
#### IaC ( Infraestructura como codigo )
- AWS CLI:https://aws.amazon.com/es/cli/
- CDK:https://docs.aws.amazon.com/cdk/v2/guide/home.html
- AWS SAM:https://aws.amazon.com/es/serverless/sam/
- Terraform:https://www.terraform.io/
- Serverless Framework: https://www.serverless.com/
- Pulumi: https://www.pulumi.com/

### Costos
- https://es.wikipedia.org/wiki/Watchmen
- Que hay en nuestra cuenta de AWS Podcast: https://www.youtube.com/watch?v=Sh2nE7_-ews 
- Cloud Insights: https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/CWL_QuerySyntax.html

## NO quiero condimentos
- CNFC landscape: https://landscape.cncf.io/ 
- Knative: https://knative.dev/docs/
- Firecraker: https://firecracker-microvm.github.io/
- OpenFaas: https://www.openfaas.com/
- Tanzu: https://tanzu.vmware.com/tanzu
- Openwhisk: https://openwhisk.apache.org/
- OpenShift: https://www.redhat.com/es/technologies/cloud-computing/openshift/try-it?sc_cid=7013a0000026OSAAA2&gclsrc=ds&gclsrc=ds

## Herramientas de la presentacion:
- QR: https://www.logodesign.net/qrcode-generator
- Google Trends: https://trends.google.es/trends/?geo=ES


## Referencias a figuras e imagenes
- https://cms.dm.uba.ar/academico/materias/2docuat2013/algebra_I/TeoricaAlgebra2013-Cap1.pdf
- https://www.verygourmand.com/es/galletas-patatas-fritas/694-tata-josie-mini-pizzetta-tomate-oregano-180g-3760153840997.html
- Historia de serverless: https://dashbird.io/blog/origin-of-serverless/
- Serverless Lamp Stack: https://aws.amazon.com/es/blogs/compute/introducing-the-new-serverless-lamp-stack/
