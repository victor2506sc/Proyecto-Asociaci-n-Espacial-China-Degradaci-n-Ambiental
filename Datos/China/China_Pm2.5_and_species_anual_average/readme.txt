============================================
README: Tracking Air Pollution in China (TAP) Data Download
============================================

This zip file will be named by six random characters (e.g. "764bfc.zip").

----------------------------------------------------------------------------

If you requested the data of near real-time PM2.5 and species product since 2000 at a 10-km spatial resolution, the following files are contained in the downloaded zip:
    YYYYMMDD_PM25_and_species.csv if daily data are requested 
    YYYYMM_PM25_and_species.csv if monthly data are requested 
    YYYY_PM25_and_species.csv if annual data are requested 
    Average_PM25_and_species.xlsx
    readme.txt

YYYYMMDD/YYYYMM/YYYY indicates the date of the requested data. The variables in the YYYY(MMDD)_PM25_and_species.csv files include:
    GridID: ID of the corresponding grid (Unitless)
    X_Lon: Longitude (Degree)
    Y_Lat:  Latitude (Degree)
    PM2.5: Daily/Monthly/Annual mean PM2.5 concerntration (μg/m3, minimum value: 1 μg/m3)
    SO4: Daily/Monthly/Annual mean sulfate concerntration (μg/m3, minimum value: 0.01 μg/m3)
    NO3: Daily/Monthly/Annual mean nitrate concerntration (μg/m3, minimum value: 0.01 μg/m3)
    NH4: Daily/Monthly/Annual mean ammonium concerntration (μg/m3, minimum value: 0.01 μg/m3)
    OM: Daily/Monthly/Annual mean organic matter concerntration (μg/m3, minimum value: 0.01 μg/m3)
    BC: Daily/Monthly/Annual mean black carbon concerntration (μg/m3, minimum value: 0.01 μg/m3)

The variables in the Average_PM25_and_species.xlsx file include:
    Date: Date in the YYYYMMDD or YYYYMM or YYYY format (Unitless)
    Region Name: Regional average daily/monthly/annual mean PM2.5 and species concentration over provincial administrative regions or the customized region (μg/m3, minimum value: 1 μg/m3 for PM2.5 and 0.01 μg/m3 for PM2.5 species)

----------------------------------------------------------------------------

If you requested the data of near real-time O3 product since 2013 (O3 data version 2) at a 10-km spatial resolution, the following files are contained in the downloaded zip:
    YYYYMMDD_O3_v2.csv if daily data are requested
    YYYYMM_O3_v2.csv if monthly data are requested
    YYYY_O3_v2.csv if annual data are requested
    Average_O3_v2.csv
    readme.txt

YYYYMMDD/YYYYMM/YYYY indicates the date of the requested data. The variables in the data files include:
    GridID: ID of the corresponding grid (Unitless)
    X_Lon: Longitude (Degree)
    Y_Lat:  Latitude (Degree)
    M8H_O3: 
          1. Maximum daily average 8-hour (MDA-8h) O3 concentration if daily data are requested (μg/m3, minimum value: 1 μg/m3)
          2. The 90th percentile of the MDA-8h O3 concentration during each month if monthly data are requested (μg/m3, minimum value: 1 μg/m3)
          3. The 90th percentile of the MDA-8h O3 concentration during each year if annual data are requested (μg/m3, minimum value: 1 μg/m3)

The variables in the Average_O3_v2.csv file include:
    Date: Date in the YYYYMMDD or YYYYMM or YYYY format (Unitless)
    Region Name: Regional average MDA-8h/monthly 90th percentile of the MDA-8h/annual 90th percentile of the MDA-8h O3 concentration over provincial administrative regions or the customized region(μg/m3, minimum value: 1 μg/m3)

----------------------------------------------------------------------------

If you requested the data of historical O3 product between 2013-2020 (O3 data version 1) at a 10-km spatial resolution, the following files are contained in the downloaded zip:
    YYYYMMDD_O3_v1.csv if daily data are requested
    YYYYMM_O3_v1.csv if monthly data are requested
    YYYY_O3_v1.csv if annual data are requested
    Average_O3_v1.csv
    readme.txt

YYYYMMDD/YYYYMM/YYYY indicates the date of the requested data. The variables in the data files include:
    GridID: ID of the corresponding grid (Unitless)
    X_Lon: Longitude (Degree)
    Y_Lat:  Latitude (Degree)
    M8H_O3: 
          1. Maximum daily average 8-hour (MDA-8h) O3 concentration if daily data are requested (μg/m3, minimum value: 1 μg/m3)
          2. The 90th percentile of the MDA-8h O3 concentration during each month if monthly data are requested (μg/m3, minimum value: 1 μg/m3)
          3. The 90th percentile of the MDA-8h O3 concentration during each year if annual data are requested (μg/m3, minimum value: 1 μg/m3)

The variables in the Average_O3_v1.csv file include:
    Date: Date in the YYYYMMDD or YYYYMM or YYYY format (Unitless)
    Region Name: Regional average MDA-8h/monthly 90th percentile of the MDA-8h/annual 90th percentile of the MDA-8h O3 concentration over provincial administrative regions or the customized region(μg/m3, minimum value: 1 μg/m3)

----------------------------------------------------------------------------

For more details regarding the data production methods, please visit the TAP website at http://tapdata.org/

============================================
PROJECTION INFORMATION
============================================
The PM2.5 and O3 data are in the WGS84 Geographic projection (the "latitude/longitude projection").

The pollution distribution map are in the Lambert Conformal projection.

============================================
DATA CITATION
============================================

If you use the PM2.5 concentration data from TAP, please cite the TAP website (http://tapdata.org) and the following papers:
Geng, G., Xiao, Q., Liu, S., Liu, X., Cheng, J., Zheng, Y., Xue, T., Tong, D., Zheng, B., Peng, Y., Huang, X., He, K., & Zhang, Q. (2021). Tracking Air Pollution in China: Near Real-Time PM2.5 Retrievals from Multisource Data Fusion. Environ Sci Technol, 55, 12106-12115.
Xiao, Q., Geng, G., Cheng, J., Liang, F., Li, R., Meng, X., Xue, T., Huang, X., Kan, H., Zhang, Q., & He, K. (2021). Evaluation of gap-filling approaches in satellite-based daily PM2.5 prediction models. Atmos Environ, 244, 117921

If you use the O3 concentration data from TAP, please cite the TAP website (http://tapdata.org) and the following paper:
Xue, T., Zheng, Y., Geng, G., Xiao, Q., Meng, X., Wang, M., Li, X., Wu, N., Zhang, Q., & Zhu, T. (2020). Estimating spatiotemporal variation in ambient ozone exposure during 2013–2017 using a data-fusion model. Environ Sci Tech, 54, 14877-14888

============================================
USER AGREEMENT
============================================
This User Agreement ("Agreement") is a contract between you and TAP team and applies to your utilization of the TAP materials and services. You must read, agree with and accept all of the terms and conditions contained in this Agreement. Any users of the TAP content regardless of sources are regarded as accepting all of the terms unconditionally. Please stop the usage if you have any objections to the following terms.

1. TAP team is committed to providing high quality atmospheric composition data and maps. Users bear all responsibility and liability for their use of data, and for any indirect, incidental or consequential damages arising out of any use of, or inability to use, the data.

2. The data and maps provided on this website is for non-commercial usage only. No organization or individual is allowed to use the TAP content for commercial purposes without prior written authorization from the TAP team. Any uses of TAP materials by commercial institutes are regarded as for commercial purposes that requires prior written authorization. For information on using TAP content for commercial purposes or for commercial organizations to apply for the usage of TAP content, please contact tap@tsinghua.edu.cn.

3. Users are not permitted to distribute the TAP content or the TAP account to any third-party, with or without payment. Any losses incurred by breaching this term shall be borne by the user. We reserve the right to ascertain his/her legal responsibilities.

4. Users are required to maintain the integrity and independence of the content from TAP. Without the permission from the TAP team, no user shall include the TAP data and maps, in the original or modified form, into other atmospheric composition data products.

5. Users are required to fully cite the relevant publications when using the TAP content. For specific citations, please refer to http://tapdata.org/?page_id=83&lang=en.

The rights to interpret, modify and update this agreement belongs to the TAP team.