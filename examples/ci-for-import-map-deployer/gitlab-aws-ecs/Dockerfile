FROM singlespa/import-map-deployer

ENV HTTP_USERNAME= HTTP_PASSWORD= AWS_DEFAULT_REGION= STAGING_S3_OBJECT_URL= PRODUCTION_S3_OBJECT_URL= AWS_CANNED_ACL=

COPY conf.js /www/

CMD ["yarn", "start", "conf.js"]
