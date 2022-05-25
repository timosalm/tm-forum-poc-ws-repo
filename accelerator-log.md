# Accelerator Log

## Options
```json
{
  "apiSpecLocation" : "remote",
  "artifactId" : "product-catalog-management-api-java",
  "database" : "mongo",
  "gitBranch" : "workshops-w02-s011-8e19f990-81d1-4574-9aa5-7a793b58f095",
  "gitUrl" : "https://github.com/tsalm-pivotal/tm-forum-poc-ws-repo.git",
  "ingressDomain" : "emea.end2end.link",
  "namespace" : "workshops-w02-s011",
  "projectName" : "tmf-product-catalog-management-api-java"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Exclude
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[0].exclude (Exclude)
┃ ┃ ┃ ┃  Info Will exclude [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml]
┃ ┃ ┃ ┃ Debug .gitignore didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug README.md didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug accelerator-deployment.yaml matched [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/apis/api.yaml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/apis/docs/index.md didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/apis/mkdocs.yml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/components/database/component-mongo.yaml matched [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/components/database/component-postgres.yaml matched [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/components/database/docs/index.md didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/components/database/mkdocs.yml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/components/service/component.yaml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/components/service/docs/index.md didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/components/service/mkdocs.yml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/docs/index.md didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/groups/department.yaml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/groups/team.yaml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/mkdocs.yml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/systems/docs/index.md didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/systems/mkdocs.yml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/systems/tmf-apis-system.yaml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug config/test-pipeline.yaml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug pom.xml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ApiUtil.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApi.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApiController.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogRepository.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApi.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApiController.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApi.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApiController.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApi.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApiController.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApi.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApiController.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApi.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApiController.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoOffsetDateTimeConversion.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoRepositoryConfiguration.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/PostgresRepositoryConfiguration.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApi.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApiController.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApi.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApiController.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApi.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApiController.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/OpenAPI2SpringBoot.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/RFC3339DateFormat.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/configuration/HomeController.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Addressable.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AgreementRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Attachment.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRefOrValue.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOffering.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingOption.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingPriceRelationship.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductSpecification.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Catalog.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreate.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogUpdate.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Category.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreate.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryUpdate.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ChannelRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicSpecificationBase.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicValueSpecification.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ConstraintRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Duration.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Entity.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EntityRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Error.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscription.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscriptionInput.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJob.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJobCreate.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Extensible.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJob.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJobCreate.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/JobStateType.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/MarketSegmentRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Money.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPAlteration.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPCharge.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PlaceRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PricingLogicAlgorithm.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOffering.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreate.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPrice.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreate.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRefOrValue.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRelationship.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceUpdate.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRelationship.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingTerm.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingUpdate.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductPriceValue.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecification.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristic.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicRelationship.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicValueUse.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreate.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRelationship.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEvent.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEventPayload.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationUpdate.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Quantity.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/RelatedParty.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceCandidateRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceSpecificationRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/SLARef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceCandidateRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceSpecificationRef.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TargetProductSchema.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TaxItem.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TimePeriod.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/openapi.yaml didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┃ Debug src/test/java/org/openapitools/OpenAPI2SpringBootTest.java didn't match [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> included
┃ ┃ ┃ ┗ Debug update-accelerator.sh matched [accelerator-deployment.yaml, update-accelerator.sh, catalog/components/database/*.yaml] -> excluded
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [config/workload.yaml]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug accelerator-deployment.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/api.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/docs/index.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/mkdocs.yml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/component-mongo.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/component-postgres.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/docs/index.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/mkdocs.yml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/component.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/docs/index.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/mkdocs.yml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/docs/index.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/department.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/team.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/mkdocs.yml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/docs/index.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/mkdocs.yml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/tmf-apis-system.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/test-pipeline.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ApiUtil.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApi.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApiController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogRepository.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApi.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApiController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApi.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApiController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApi.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApiController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApi.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApiController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApi.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApiController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoOffsetDateTimeConversion.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoRepositoryConfiguration.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/PostgresRepositoryConfiguration.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApi.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApiController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApi.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApiController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApi.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApiController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/OpenAPI2SpringBoot.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/RFC3339DateFormat.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/configuration/HomeController.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Addressable.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AgreementRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Attachment.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRefOrValue.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOffering.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingOption.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingPriceRelationship.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductSpecification.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Catalog.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreate.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogUpdate.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Category.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreate.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryUpdate.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ChannelRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicSpecificationBase.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicValueSpecification.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ConstraintRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Duration.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Entity.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EntityRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Error.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscription.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscriptionInput.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJob.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJobCreate.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Extensible.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJob.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJobCreate.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/JobStateType.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/MarketSegmentRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Money.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPAlteration.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPCharge.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PlaceRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PricingLogicAlgorithm.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOffering.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreate.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPrice.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreate.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRefOrValue.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRelationship.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceUpdate.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRelationship.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingTerm.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingUpdate.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductPriceValue.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecification.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristic.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicRelationship.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicValueUse.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreate.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRelationship.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEvent.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEventPayload.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationUpdate.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Quantity.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/RelatedParty.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceCandidateRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceSpecificationRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/SLARef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceCandidateRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceSpecificationRef.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TargetProductSchema.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TaxItem.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TimePeriod.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/openapi.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/openapitools/OpenAPI2SpringBootTest.java didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug update-accelerator.sh didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [default->workshops-w02-s011, https://github.com/tsalm-pivotal/tm-forum-java.git->https://github.com/t...(truncated), main->workshops-w02-s011-8...(truncated), tmf-product-catalog-management-api-java->product-catalog-mana...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#database == 'postgres') evaluated to false
┃ ┃ ┃ ┗ ┗ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**/*.java, **/*.properties]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug accelerator-deployment.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/api.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/docs/index.md didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/mkdocs.yml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/component-mongo.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/component-postgres.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/docs/index.md didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/mkdocs.yml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/component.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/docs/index.md didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/mkdocs.yml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/docs/index.md didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/department.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/team.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/mkdocs.yml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/docs/index.md didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/mkdocs.yml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/tmf-apis-system.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/test-pipeline.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ApiUtil.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApi.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApiController.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogRepository.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApi.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApiController.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApi.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApiController.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApi.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApiController.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApi.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApiController.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApi.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApiController.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoOffsetDateTimeConversion.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoRepositoryConfiguration.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/PostgresRepositoryConfiguration.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApi.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApiController.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApi.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApiController.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApi.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApiController.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/OpenAPI2SpringBoot.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/RFC3339DateFormat.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/configuration/HomeController.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Addressable.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AgreementRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Attachment.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRefOrValue.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOffering.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingOption.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingPriceRelationship.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductSpecification.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Catalog.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreate.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogUpdate.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Category.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreate.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryUpdate.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ChannelRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicSpecificationBase.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicValueSpecification.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ConstraintRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Duration.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Entity.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EntityRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Error.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscription.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscriptionInput.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJob.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJobCreate.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Extensible.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJob.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJobCreate.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/JobStateType.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/MarketSegmentRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Money.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPAlteration.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPCharge.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PlaceRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PricingLogicAlgorithm.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOffering.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreate.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPrice.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreate.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRefOrValue.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRelationship.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceUpdate.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRelationship.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingTerm.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingUpdate.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductPriceValue.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecification.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristic.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicRelationship.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicValueUse.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreate.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRelationship.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEvent.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEventPayload.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationUpdate.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Quantity.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/RelatedParty.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceCandidateRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceSpecificationRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/SLARef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceCandidateRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceSpecificationRef.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TargetProductSchema.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TaxItem.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TimePeriod.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/openapi.yaml didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/openapitools/OpenAPI2SpringBootTest.java matched [**/*.java, **/*.properties] -> included
┃ ┃ ┃ ┃ ┗ Debug update-accelerator.sh didn't match [**/*.java, **/*.properties] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, RewritePath, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex 'com.vodafone' with 'com.vodafone'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[1].transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/ApiUtil.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ApiUtil.java, g1=ApiUtil.java} and was rewritten to 'src/main/java/com/vodafone/ApiUtil.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/CatalogApi.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/CatalogApi.java, g1=CatalogApi.java} and was rewritten to 'src/main/java/com/vodafone/CatalogApi.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/CatalogApiController.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/CatalogApiController.java, g1=CatalogApiController.java} and was rewritten to 'src/main/java/com/vodafone/CatalogApiController.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/CatalogRepository.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/CatalogRepository.java, g1=CatalogRepository.java} and was rewritten to 'src/main/java/com/vodafone/CatalogRepository.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/CategoryApi.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/CategoryApi.java, g1=CategoryApi.java} and was rewritten to 'src/main/java/com/vodafone/CategoryApi.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/CategoryApiController.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/CategoryApiController.java, g1=CategoryApiController.java} and was rewritten to 'src/main/java/com/vodafone/CategoryApiController.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/ExportJobApi.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ExportJobApi.java, g1=ExportJobApi.java} and was rewritten to 'src/main/java/com/vodafone/ExportJobApi.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/ExportJobApiController.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ExportJobApiController.java, g1=ExportJobApiController.java} and was rewritten to 'src/main/java/com/vodafone/ExportJobApiController.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/HubApi.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/HubApi.java, g1=HubApi.java} and was rewritten to 'src/main/java/com/vodafone/HubApi.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/HubApiController.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/HubApiController.java, g1=HubApiController.java} and was rewritten to 'src/main/java/com/vodafone/HubApiController.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/ImportJobApi.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ImportJobApi.java, g1=ImportJobApi.java} and was rewritten to 'src/main/java/com/vodafone/ImportJobApi.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/ImportJobApiController.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ImportJobApiController.java, g1=ImportJobApiController.java} and was rewritten to 'src/main/java/com/vodafone/ImportJobApiController.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/ListenerApi.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ListenerApi.java, g1=ListenerApi.java} and was rewritten to 'src/main/java/com/vodafone/ListenerApi.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/ListenerApiController.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ListenerApiController.java, g1=ListenerApiController.java} and was rewritten to 'src/main/java/com/vodafone/ListenerApiController.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/MongoOffsetDateTimeConversion.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/MongoOffsetDateTimeConversion.java, g1=MongoOffsetDateTimeConversion.java} and was rewritten to 'src/main/java/com/vodafone/MongoOffsetDateTimeConversion.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/MongoRepositoryConfiguration.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/MongoRepositoryConfiguration.java, g1=MongoRepositoryConfiguration.java} and was rewritten to 'src/main/java/com/vodafone/MongoRepositoryConfiguration.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/PostgresRepositoryConfiguration.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/PostgresRepositoryConfiguration.java, g1=PostgresRepositoryConfiguration.java} and was rewritten to 'src/main/java/com/vodafone/PostgresRepositoryConfiguration.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/ProductOfferingApi.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ProductOfferingApi.java, g1=ProductOfferingApi.java} and was rewritten to 'src/main/java/com/vodafone/ProductOfferingApi.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/ProductOfferingApiController.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ProductOfferingApiController.java, g1=ProductOfferingApiController.java} and was rewritten to 'src/main/java/com/vodafone/ProductOfferingApiController.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/ProductOfferingPriceApi.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ProductOfferingPriceApi.java, g1=ProductOfferingPriceApi.java} and was rewritten to 'src/main/java/com/vodafone/ProductOfferingPriceApi.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/ProductOfferingPriceApiController.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ProductOfferingPriceApiController.java, g1=ProductOfferingPriceApiController.java} and was rewritten to 'src/main/java/com/vodafone/ProductOfferingPriceApiController.java'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'src/main/java/com/vodafone/ProductSpecificationApi.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ProductSpecificationApi.java, g1=ProductSpecificationApi.java} and was rewritten to 'src/main/java/com/vodafone/ProductSpecificationApi.java'
┃ ┃ ┃ ┃ ┃ ┗ Debug Path 'src/main/java/com/vodafone/ProductSpecificationApiController.java' matched 'src/main/java/com/vodafone/(.*)' with groups {g0=src/main/java/com/vodafone/ProductSpecificationApiController.java, g1=ProductSpecificationApiController.java} and was rewritten to 'src/main/java/com/vodafone/ProductSpecificationApiController.java'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[1].transformations[2] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [database=mongo->database=mongo]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[3].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [pom.xml]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug accelerator-deployment.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/api.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/docs/index.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/mkdocs.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/component-mongo.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/component-postgres.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/docs/index.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/mkdocs.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/component.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/docs/index.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/mkdocs.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/docs/index.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/department.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/team.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/mkdocs.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/docs/index.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/mkdocs.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/tmf-apis-system.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/test-pipeline.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ApiUtil.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApi.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApiController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogRepository.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApi.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApiController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApi.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApiController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApi.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApiController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApi.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApiController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApi.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApiController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoOffsetDateTimeConversion.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoRepositoryConfiguration.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/PostgresRepositoryConfiguration.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApi.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApiController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApi.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApiController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApi.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApiController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/OpenAPI2SpringBoot.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/RFC3339DateFormat.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/configuration/HomeController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Addressable.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AgreementRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Attachment.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRefOrValue.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOffering.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingOption.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingPriceRelationship.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductSpecification.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Catalog.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreate.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogUpdate.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Category.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreate.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryUpdate.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ChannelRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicSpecificationBase.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicValueSpecification.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ConstraintRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Duration.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Entity.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EntityRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Error.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscription.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscriptionInput.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJob.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJobCreate.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Extensible.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJob.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJobCreate.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/JobStateType.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/MarketSegmentRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Money.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPAlteration.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPCharge.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PlaceRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PricingLogicAlgorithm.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOffering.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreate.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPrice.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreate.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRefOrValue.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRelationship.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceUpdate.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRelationship.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingTerm.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingUpdate.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductPriceValue.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecification.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristic.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicRelationship.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicValueUse.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreate.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRelationship.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEvent.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEventPayload.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationUpdate.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Quantity.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/RelatedParty.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceCandidateRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceSpecificationRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/SLARef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceCandidateRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceSpecificationRef.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TargetProductSchema.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TaxItem.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TimePeriod.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/openapi.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/openapitools/OpenAPI2SpringBootTest.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug update-accelerator.sh didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[3].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [tmf-product-catalog-management-api->product-catalog-mana...(truncated), '´<java.version>1.8</java.version>-><java.version>11</ja...(truncated), <version>2.6.2</version>-><version>2.6.6</vers...(truncated), <groupId>com.vodafone</groupId>'-><groupId>com.vodafon...(truncated)]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[4].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [catalog/catalog-info.yaml]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug accelerator-deployment.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/api.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/docs/index.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/mkdocs.yml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/catalog-info.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/component-mongo.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/component-postgres.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/docs/index.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/mkdocs.yml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/component.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/docs/index.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/mkdocs.yml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/docs/index.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/department.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/team.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/mkdocs.yml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/docs/index.md didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/mkdocs.yml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/tmf-apis-system.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/test-pipeline.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ApiUtil.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApi.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApiController.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogRepository.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApi.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApiController.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApi.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApiController.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApi.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApiController.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApi.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApiController.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApi.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApiController.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoOffsetDateTimeConversion.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoRepositoryConfiguration.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/PostgresRepositoryConfiguration.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApi.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApiController.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApi.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApiController.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApi.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApiController.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/OpenAPI2SpringBoot.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/RFC3339DateFormat.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/configuration/HomeController.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Addressable.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AgreementRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Attachment.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRefOrValue.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOffering.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingOption.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingPriceRelationship.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductSpecification.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Catalog.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreate.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogUpdate.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Category.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreate.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryUpdate.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ChannelRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicSpecificationBase.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicValueSpecification.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ConstraintRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Duration.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Entity.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EntityRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Error.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscription.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscriptionInput.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJob.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJobCreate.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Extensible.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJob.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJobCreate.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/JobStateType.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/MarketSegmentRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Money.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPAlteration.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPCharge.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PlaceRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PricingLogicAlgorithm.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOffering.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreate.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPrice.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreate.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRefOrValue.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRelationship.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceUpdate.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRelationship.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingTerm.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingUpdate.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductPriceValue.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecification.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristic.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicRelationship.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicValueUse.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreate.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRelationship.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEvent.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEventPayload.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationUpdate.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Quantity.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/RelatedParty.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceCandidateRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceSpecificationRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/SLARef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceCandidateRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceSpecificationRef.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TargetProductSchema.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TaxItem.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TimePeriod.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/openapi.yaml didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/openapitools/OpenAPI2SpringBootTest.java didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug update-accelerator.sh didn't match [catalog/catalog-info.yaml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[4].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [component-mongo.yaml->component-mongo.yaml]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[5].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[5].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [catalog/apis/api.yaml]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug accelerator-deployment.yaml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/api.yaml matched [catalog/apis/api.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/docs/index.md didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/apis/mkdocs.yml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/component-mongo.yaml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/component-postgres.yaml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/docs/index.md didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/database/mkdocs.yml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/component.yaml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/docs/index.md didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/service/mkdocs.yml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/docs/index.md didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/department.yaml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/team.yaml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/mkdocs.yml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/docs/index.md didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/mkdocs.yml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/tmf-apis-system.yaml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/test-pipeline.yaml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ApiUtil.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApi.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApiController.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogRepository.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApi.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApiController.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApi.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApiController.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApi.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApiController.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApi.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApiController.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApi.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApiController.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoOffsetDateTimeConversion.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoRepositoryConfiguration.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/PostgresRepositoryConfiguration.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApi.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApiController.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApi.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApiController.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApi.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApiController.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/OpenAPI2SpringBoot.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/RFC3339DateFormat.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/configuration/HomeController.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Addressable.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AgreementRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Attachment.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRefOrValue.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOffering.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingOption.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingPriceRelationship.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductSpecification.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Catalog.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreate.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogUpdate.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Category.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreate.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryUpdate.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ChannelRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicSpecificationBase.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicValueSpecification.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ConstraintRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Duration.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Entity.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EntityRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Error.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscription.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscriptionInput.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJob.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJobCreate.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Extensible.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJob.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJobCreate.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/JobStateType.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/MarketSegmentRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Money.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPAlteration.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPCharge.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PlaceRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PricingLogicAlgorithm.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOffering.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreate.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPrice.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreate.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRefOrValue.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRelationship.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceUpdate.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRelationship.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingTerm.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingUpdate.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductPriceValue.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecification.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristic.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicRelationship.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicValueUse.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreate.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRelationship.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEvent.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEventPayload.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationUpdate.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Quantity.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/RelatedParty.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceCandidateRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceSpecificationRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/SLARef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceCandidateRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceSpecificationRef.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TargetProductSchema.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TaxItem.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TimePeriod.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/openapi.yaml didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/openapitools/OpenAPI2SpringBootTest.java didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug update-accelerator.sh didn't match [catalog/apis/api.yaml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[5].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[5].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#apiSpecLocation == 'remote') evaluated to true
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [../../src/main/resources/openapi.yaml->https://product-cata...(truncated)]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[6] (Combo)
┃ ┃ ┃ ┃  Info Condition (#database == 'postgres') evaluated to false
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[7] (Combo)
┃ ┃ ┃ ┃  Info Condition (#database == 'mongo') evaluated to true
┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[7].include (Include)
┃ ┃ ┃ ┃  Info Condition (#database == 'mongo') evaluated to true
┃ ┃ ┃ ┃  Info Will include [catalog/components/database/component-mongo.yaml]
┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug accelerator-deployment.yaml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/apis/api.yaml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/apis/docs/index.md didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/apis/mkdocs.yml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/components/database/component-mongo.yaml matched [catalog/components/database/component-mongo.yaml] -> included
┃ ┃ ┃ ┃ Debug catalog/components/database/component-postgres.yaml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/components/database/docs/index.md didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/components/database/mkdocs.yml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/components/service/component.yaml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/components/service/docs/index.md didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/components/service/mkdocs.yml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/docs/index.md didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/groups/department.yaml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/groups/team.yaml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/mkdocs.yml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/systems/docs/index.md didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/systems/mkdocs.yml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug catalog/systems/tmf-apis-system.yaml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug config/test-pipeline.yaml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug pom.xml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ApiUtil.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApi.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogApiController.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CatalogRepository.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApi.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/CategoryApiController.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApi.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ExportJobApiController.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApi.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/HubApiController.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApi.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ImportJobApiController.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApi.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ListenerApiController.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoOffsetDateTimeConversion.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/MongoRepositoryConfiguration.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/PostgresRepositoryConfiguration.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApi.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingApiController.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApi.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductOfferingPriceApiController.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApi.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/vodafone/ProductSpecificationApiController.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/OpenAPI2SpringBoot.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/RFC3339DateFormat.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/configuration/HomeController.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Addressable.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AgreementRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Attachment.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/AttachmentRefOrValue.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOffering.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingOption.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductOfferingPriceRelationship.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/BundledProductSpecification.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Catalog.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogAttributeValueChangeEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogBatchEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreate.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogCreateEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogDeleteEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogStateChangeEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CatalogUpdate.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Category.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryAttributeValueChangeEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreate.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryCreateEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryDeleteEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryStateChangeEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CategoryUpdate.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ChannelRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicSpecificationBase.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/CharacteristicValueSpecification.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ConstraintRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Duration.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Entity.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EntityRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Error.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscription.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/EventSubscriptionInput.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJob.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ExportJobCreate.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Extensible.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJob.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ImportJobCreate.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/JobStateType.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/MarketSegmentRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Money.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPAlteration.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/POPCharge.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PlaceRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/PricingLogicAlgorithm.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOffering.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreate.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingCreateEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingDeleteEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPrice.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreate.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceCreateEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRefOrValue.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceRelationship.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingPriceUpdate.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingRelationship.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingStateChangeEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingTerm.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductOfferingUpdate.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductPriceValue.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecification.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristic.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicRelationship.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCharacteristicValueUse.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreate.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationCreateEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationDeleteEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationRelationship.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEvent.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationStateChangeEventPayload.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ProductSpecificationUpdate.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/Quantity.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/RelatedParty.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceCandidateRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ResourceSpecificationRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/SLARef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceCandidateRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/ServiceSpecificationRef.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TargetProductSchema.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TaxItem.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/org/openapitools/model/TimePeriod.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/resources/application.properties didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/main/resources/openapi.yaml didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┃ ┃ Debug src/test/java/org/openapitools/OpenAPI2SpringBootTest.java didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┗ ┗ Debug update-accelerator.sh didn't match [catalog/components/database/component-mongo.yaml] -> excluded
┃ ┃ ┏ engine.transformations[0].merge.transformations[1] (UniquePath)
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingCreate.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CatalogDeleteEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CategoryRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationCreateEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CategoryCreateEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingTerm.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductPriceValue.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/HubApi.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/HubApiController.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationStateChangeEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPrice.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CharacteristicValueSpecification.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/Addressable.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/PostgresRepositoryConfiguration.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/POPCharge.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CatalogAttributeValueChangeEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/BundledProductOfferingPriceRelationship.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/TaxItem.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/OpenAPI2SpringBoot.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CategoryDeleteEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ApiUtil.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/Money.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecification.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/PlaceRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CategoryAttributeValueChangeEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingRelationship.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CatalogDeleteEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ServiceCandidateRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CategoryDeleteEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ResourceSpecificationRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CategoryStateChangeEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/MongoOffsetDateTimeConversion.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/SLARef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingUpdate.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceRelationship.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/MongoRepositoryConfiguration.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/AttachmentRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/Category.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CatalogAttributeValueChangeEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/Attachment.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ServiceSpecificationRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ImportJobApi.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationStateChangeEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceDeleteEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceCreateEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'pom.xml', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/EventSubscriptionInput.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/RFC3339DateFormat.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/TargetProductSchema.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ImportJobCreate.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingDeleteEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationDeleteEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CategoryStateChangeEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ProductSpecificationApiController.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/Quantity.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationCharacteristic.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/configuration/HomeController.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationAttributeValueChangeEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/MarketSegmentRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/CategoryApi.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/POPAlteration.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/BundledProductOfferingOption.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'catalog/catalog-info.yaml', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CatalogCreateEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/BundledProductOffering.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/CategoryApiController.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationCharacteristicValueUse.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ProductOfferingPriceApi.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CatalogBatchEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ProductOfferingPriceApiController.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ExportJobApi.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CatalogCreateEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationCreate.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingCreateEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/JobStateType.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceCreate.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ListenerApi.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/RelatedParty.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ListenerApiController.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CategoryUpdate.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/application.properties', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CatalogUpdate.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/org/openapitools/OpenAPI2SpringBootTest.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceRefOrValue.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ExportJobApiController.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationUpdate.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ProductOfferingApiController.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CatalogStateChangeEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ConstraintRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceUpdate.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/EntityRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/Error.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ExportJobCreate.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CatalogCreate.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationDeleteEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/AttachmentRefOrValue.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CategoryAttributeValueChangeEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingStateChangeEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ExportJob.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/CatalogApi.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationCreateEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/Entity.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/CatalogRepository.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ImportJobApiController.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'catalog/apis/api.yaml', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ChannelRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationRelationship.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CharacteristicSpecificationBase.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ResourceCandidateRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/EventSubscription.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ProductOfferingApi.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/Duration.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/PricingLogicAlgorithm.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/AgreementRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CategoryCreateEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/BundledProductSpecification.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/TimePeriod.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceAttributeValueChangeEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingCreateEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CatalogStateChangeEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingRef.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/Extensible.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CatalogBatchEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingAttributeValueChangeEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/CatalogApiController.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingDeleteEvent.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingStateChangeEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'config/workload.yaml', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ImportJob.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductSpecificationCharacteristicRelationship.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceStateChangeEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOffering.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/vodafone/ProductSpecificationApi.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/ProductOfferingPriceCreateEventPayload.java', will use the one appearing last 
┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/org/openapitools/model/CategoryCreate.java', will use the one appearing last 
┃ ┗ ┗ Debug Multiple representations for path 'src/main/java/org/openapitools/model/Catalog.java', will use the one appearing last 
┗ ╺ engine.transformations[1] (UniquePath)
```
