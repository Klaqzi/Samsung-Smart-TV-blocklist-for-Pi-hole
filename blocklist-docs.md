Smart-TV Blocklist for Pi-hole Documentation
Version: 22.02.2026
Description: collection of domains used by my Samsung Smart TV for telemetry, tracking, ACR, ads, and unwanted network activity

---

This file explains **what each domain does**, grouped by service
It complements the 'blocklist.txt' file, which contains only raw domains for the Pi-hole

For each domain:
- **Category** gives a quick classification (telemetry, ads, ACR, analytics, etc.)
- **Description** summarizes its purpose or impact  
- **Notes** may include warnings if blocking breaks features

---

## Samsung

| Domain | Category | Description | Notes |
|--------|----------|-------------|-------|
| apu.samsungelectronics.com | Telemetry | General Samsung telemetry | Regex: `[a-z]pu.samsungelectronics.com` |
| bpu.samsungelectronics.com | Telemetry |  | |
| cpu.samsungelectronics.com | Telemetry |  | |
| dpu.samsungelectronics.com | Telemetry |  | |
| epu.samsungelectronics.com | Telemetry |  | |
| fpu.samsungelectronics.com | Telemetry |  | |
| gpu.samsungelectronics.com | Telemetry |  | |
| hpu.samsungelectronics.com | Telemetry |  | |
| ipu.samsungelectronics.com | Telemetry |  | |
| jpu.samsungelectronics.com | Telemetry |  | |
| kpu.samsungelectronics.com | Telemetry |  | |
| lpu.samsungelectronics.com | Telemetry |  | |
| mpu.samsungelectronics.com | Telemetry |  | |
| npu.samsungelectronics.com | Telemetry |  | |
| opu.samsungelectronics.com | Telemetry |  | |
| ppu.samsungelectronics.com | Telemetry |  | |
| qpu.samsungelectronics.com | Telemetry |  | |
| rpu.samsungelectronics.com | Telemetry |  | |
| spu.samsungelectronics.com | Telemetry |  | |
| tpu.samsungelectronics.com | Telemetry |  | |
| upu.samsungelectronics.com | Telemetry |  | |
| vpu.samsungelectronics.com | Telemetry |  | |
| wpu.samsungelectronics.com | Telemetry |  | |
| xpu.samsungelectronics.com | Telemetry |  | |
| ypu.samsungelectronics.com | Telemetry |  | |
| zpu.samsungelectronics.com | Telemetry |  | |
| acr-eu-prd.samsungcloud.tv | ACR | Automatic Content Recognition (tracks what you watch incl. HDMI sources) | High privacy impact |
| log-config.samsungacr.com | ACR | Configuration service for Samsung ACR | |
| log-ingestion-eu.samsungacr.com | ACR |  | |
| config.samsungads.com | Ads | targeted ads, tracks user engagement | |
| tvx.adgrx.com | Ads | monitors watched content for targeted ads | |
| rtb.adgrx.com | Ads | real-time bidding for targeted ads | |
| oempprd.samsungcloudsolution.com | System | manages app installation | |
| empdownprd.samsungcloudsolution.com | Tracking | used for tracking | might cause SmartHub issues |
| ocfconnect-shard-eu02-euwest1.samsungiotcloud.com | — | — | |
| otnprd8.samsungcloudsolution.net | — | — | |
| otnprd9.samsungcloudsolution.net | — | — | |
| otnprd10.samsungcloudsolution.net | — | — | |
| otnprd11.samsungcloudsolution.net | — | — | |

---

## Netflix

| Domain | Category | Description | Notes |
|--------|----------|-------------|-------|
| ichnaea.netflix.com | — | preview for shows on Netflix | |
| customerevents.netflix.com | Telemetry | alias of beacon.netflix.com, used for telemetry, logging and analytical data | |
| logs.netflix.com | Telemetry | telemetry etc. | |

---

## Google / YouTube

| Domain | Category | Description | Notes |
|--------|----------|-------------|-------|
| www.google-analytics.com | Telemetry | telemetry etc. | |

---

## German TV

### ARD / ZDF / HD+

| Domain | Category | Description | Notes |
|--------|----------|-------------|-------|
| images.ardmediathek.de | — | ARD | |
| audit.nmrodam.com | — | — | |
| hbbtv.zdf.de | — | ZDF | |
| be.tvengine.hd-plus-cloud.de | — | HD+TV Germany, platform for satellite and internet TV | |
| device-manager.hdplus.yottacloud.net | — | — | |
| tvengine.hd-plus-cloud.de | — | — | |
| img.welt.de | — | Welt.de | |
| www.welt.de | — | Welt.de | |

### itsmy.TV

| Domain | Category | Description | Notes |
|--------|----------|-------------|-------|
| cdn10.itsmy.tv | — | itsmy.TV, according to Google for games, seems dead since 2014??, origins in Munich | |
| cdn11.itsmy.tv | — | — | |
| cdn12.itsmy.tv | — | — | |
| cdn13.itsmy.tv | — | — | |
| cdn14.itsmy.tv | — | — | |
| cdn15.itsmy.tv | — | — | |

---

## Rakuten TV

| Domain | Category | Description | Notes |
|--------|----------|-------------|-------|
| images-0.wuaki.tv | — | — | |
| images-1.wuaki.tv | — | — | |
| images-2.wuaki.tv | — | — | |
| images-3.wuaki.tv | — | — | |

---

## Nielsen

| Domain | Category | Description | Notes |
|--------|----------|-------------|-------|
| 41697968db8a7aa24710d53c7d84e7c2.redinuid.imrworldwide.com | Analytics | Nielsen, company for marketing research, data analytics | |
| cde609cab573bb126226c829b0791957.redinuid.imrworldwide.com | Analytics | — | |

---

## Disney

| Domain | Category | Description | Notes |
|--------|----------|-------------|-------|
| config-cd-dmgz.bamgrid.com | — | Disney Streaming | |
| disney-curated-partner-feeds-prod.bamgrid.com | — | — | |

---

## Other Services

| Domain | Category | Description | Notes |
|--------|----------|-------------|-------|
| resources.redbull.tv | — | Red Bull TV | |
| sportworld-images.watchmi.tv | — | Sportworld | |
| seat-cupra-pk0700-cdn.tvapp-server.de | — | Cupra TV-App | |
| schauinsland-pk1937-cdn.tvapp-server.de | — | TV-App, no idea what it's used for | |


# watchlist

# cdn-0.nflximg.com		#
# nrdp.prod.cloud.netflix.com
# nrdp.nccp.netflix.com
# occ-0-1556-1555.1.nflxso.net
# push.prod.netflix.com
# api-global.netflix.com
# uiboot.netflix.com
# www.google-analytics.com
# nrdp52-appboot.netflix.com


# found online:

abtauthprd.samsungcloudsolution.com
ad.samsungadhub.com
ads.samsungads.com
amauthprd.samsungcloudsolution.com
api-hub.samsungyosemite.com
az43064.vo.msecnd.net
cdn.samsungcloudsolution.net
connecttv.pelmorex.com # weather app tracking
Coordinator-Production-28516768.us-east-1.elb.amazonaws.com
cpu.samsungelectronics.com
d179kwmlpc4o47.cloudfront.net
d1jwpcr0q4pcq0.cloudfront.net
d1oxlq5h9kq8q5.cloudfront.net # app icons in samsung app store
d2tnx644ijgq6i.cloudfront.net
d3mjsomixevyw7.cloudfront.net
d37ju0xanoz6gh.cloudfront.net
device-metrics-us.amazon.com
fkp.samsungcloudsolution.com
fkp.samsungcloudsolution.net
game.internetat.tv
gld.samsungosp.com
#gpm.samsungqbe.com # Numerous connection problems, e.g. #82
i-stream.pl
log-1.samsungacr.com
log-2.samsungacr.com
log-3.samsungacr.com
log-ingestion.samsungacr.com
log-ingestion-eu.samsungacr.com
log.internetat.tv
musicid.samsungcloudsolution.com
notice.samsungcloudsolution.com
noticecdn.samsungcloudsolution.com
noticefile.samsungcloudsolution.com
oempprd.samsungcloudsolution.com
oempprd.samsungcloudsolution.net
prderrordumphsm.samsungcloudsolution.com
openapi.samsung.com
osb-apps-v2.samsungqbe.com
osb-krsvc.samsungqbe.com
osb-eusvc.samsungqbe.com
osb.samsungqbe.com
pavv.co.kr
pipeaota.com
premium-videos.telly.com
prov.samsungcloudsolution.com
rd.samsungadhub.com
www.samsungotn.net
samsungacr.com
samsungadhub.com
samsungcloudsolution.com
samsungcloudsolution.net
samsungqbe.com
sas.samsungcloudsolution.com
sca.samsung.com
sso.internetat.tv # account login
syncplusconfig.s3.amazonaws.com
targeted-config-test.samsungacr.com
test.samsungrm.net
us-api.samsungyosemite.com
vd.emp.prd.s3.amazonaws.com
vdterms.samsungcloudsolution.com
www.samsungrm.net
samsungelectronics.com
apu.samsungelectronics.com
bpu.samsungelectronics.com
dpu.samsungelectronics.com
kpu.samsungelectronics.com
upu.samsungelectronics.com
zpu.samsungelectronics.com
xpu.samsungelectronics.com
ypu.samsungelectronics.com
vd.contents.prod.eu.s3.amazonaws.com
data.arqiva.tv
cloud.arqiva.tv
ads.aimitv.com
samsungads.com
gamespromotion.samsungcloudsolution.com


