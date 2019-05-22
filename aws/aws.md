Alternative naming schemes for AWS regions
==========================================

Purpose
-------

The intent is to define terse, standards-supported names for AWS regions.

Schemes
-------

| Region        | Location      | Partition    | Launched | AWS code         | A1      | A2      | B       |
|---------------|---------------|--------------|----------|------------------|---------|---------|---------|
| US East       | N. Virginia   | `aws`        | 2006     | `us-east-1`      | `usea1` | `use1`  | `usva`  |
| US East       | Ohio          | `aws`        | 2016     | `us-east-2`      | `usea2` | `use2`  | `usoh`  |
| US West       | N. California | `aws`        | 2011     | `us-west-1`      | `uswe1` | `usw1`  | `usca`  |
| US West       | Oregon        | `aws`        | 2009     | `us-west-2`      | `uswe2` | `usw2`  | `usor`  |
| GovCloud US   | Northwest     | `aws-us-gov` | 2011     | `us-gov-west-1`  | `ugwe2` | `usgw2` | `usgov` |
| Canada        | Montreal      | `aws`        | 2016     | `ca-central-1`   | `cace1` | `cac1`  | `caqc`  |
| EU            | Ireland       | `aws`        | 2007     | `eu-west-1`      | `euwe1` | `ew1`   | `ied`   |
| EU            | London        | `aws`        | 2016     | `eu-west-2`      | `euwe2` | `ew2`   | `gblnd` |
| EU            | Frankfurt     | `aws`        | 2014     | `eu-central-1`   | `euce1` | `ec1`   | `dehe`  |
| Asia Pacific  | Singapore     | `aws`        | 2010     | `ap-southeast-1` | `apse1` | `apse1` | `sg`    |
| Asia Pacific  | Sydney        | `aws`        | 2012     | `ap-southeast-2` | `apse2` | `apse2` | `aunsw` |
| Asia Pacific  | Mumbai        | `aws`        | 2016     | `ap-south-1`     | `apso1` | `aps1`  | `inmh`  |
| Asia Pacific  | Tokyo         | `aws`        | 2011     | `ap-northeast-1` | `apne1` | `apne1` | `jp13`  |
| Asia Pacific  | Seoul         | `aws`        | 2016     | `ap-northeast-2` | `apne2` | `apne2` | `kr11`  |
| South America | Saõ Paulo     | `aws`        | 2011     | `sa-east-1`      | `saea1` | `sae1`  | `brsp`  |
| China         | Beijing       | `aws-cn`     | 2013     | `cn-north-1`     | `cnno1` | `cn1`   | `cn11`  |

| Code | Description                         |
|------|-------------------------------------|
| A1   | Abbreviated AWS code (equal length) |
| A2   | Abbreviated AWS code                |
| B    | Concatenated ISO 3166 code          |

### Domain names for regional services

| AWS code         | Domain 1           | Domain 2        |
|------------------|--------------------|-----------------|
| `us-east-1`      | example-va.us      | example.us      |
| `us-west-1`      | example-ca.us      | example-west.us |
| `us-west-2`      | example-or.us      | example-nw.us   |
| `eu-west-1`      | example-d.ie       | example.ie      |
| `eu-west-2`      | example-lnd.net.uk | example.net.uk  |
| `eu-central-1`   | example-he.de      | example.de      |
| `ap-southeast-1` | example.sg         | example.sg      |
| `ap-southeast-2` | example-nsw.net.au | example.net.au  |
| `ap-northeast-1` | example-13.jp      | example.jp      |
| `ap-northeast-2` | example.seoul.kr   | example.ne.kr   |
| `sa-east-1`      | example-sp.net.br  | example.net.br  |
| `cn-north-1`     | example.bj.cn      | example.cn      |

### Capital-delimited codes for variable-width fonts

| AWS code         | A1      | A2    | B     |
|------------------|---------|-------|-------|
| `us-east-1`      | `USea1` | USe1  | USva  |
| `us-west-1`      | `USwe1` | USw1  | USca  |
| `us-west-2`      | `USwe2` | USw2  | USor  |
| `us-gov-west-1`  | `gUSwe1`| gUSw1 | gUSnw |
| `eu-west-1`      | `EUwe1` | Ew1   | IEd   |
| `eu-west-2`      | `EUwe2` | Ew2   | GBlnd |
| `eu-central-1`   | `EUce1` | Ec1   | DEhe  |
| `ap-southeast-1` | `APse1` | APse1 | SG    |
| `ap-southeast-2` | `APse2` | APse2 | AUnsw |
| `ap-northeast-1` | `APne1` | APne1 | JP13  |
| `ap-northeast-2` | `APne2` | APne2 | KR11  |
| `sa-east-1`      | `SAea1` | SAe1  | BRsp  |
| `cn-north-1`     | `CNno1` | Cn1   | CN11  |

### Bold-delimited codes for rich text
| AWS code         | A1        | A2        | A2c       | B         |
|------------------|-----------|-----------|-----------|-----------|
| `us-east-1`      | **us**ea1 | **us**e1  | **US**E1  | **us**va  |
| `us-west-1`      | **us**we1 | **us**w1  | **US**W1  | **us**ca  |
| `us-west-2`      | **us**we2 | **us**w2  | **US**W2  | **us**or  |
| `us-gov-west-1`  | gov**us**we1 | gov**us**w1 | **USg**W1 | gov**us**nw |
| `eu-west-1`      | **eu**we1 | **e**w1   | **E**W1   | **ie**d   |
| `eu-west-2`      | **eu**we2 | **e**w2   | **E**W2   | **gb**lnd |
| `eu-central-1`   | **eu**ce1 | **e**c1   | **E**C1   | **de**he  |
| `ap-southeast-1` | **ap**se1 | **ap**se1 | **AP**SE1 | **sg**    |
| `ap-southeast-2` | **ap**se2 | **ap**se2 | **AP**SE2 | **au**nsw |
| `ap-northeast-1` | **ap**ne1 | **ap**ne1 | **AP**NE1 | **jp**13  |
| `ap-northeast-2` | **ap**ne2 | **ap**ne2 | **AP**NE2 | **kr**11  |
| `sa-east-1`      | **sa**ea1 | **sa**e1  | **SA**E1  | **br**sp  |
| `cn-north-1`     | **cn**no1 | **c**n1   | **C**N1   | **cn**11  |
