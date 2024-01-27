
library(tidyverse)
library(sf)
library(mapproj)

# 대한민국 최신 행정구역(SHP) 다운로드
# http://www.gisdeveloper.co.kr/?p=2332
st_read('/Users/dshin/DataspellProjects/Pcheon/Map/emd_20230729/emd.shp') ->tdf
# https://lostineconomics.netlify.app/post/2017/11/03/sf-package-with-ggplot2/
