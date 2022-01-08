# Exploratory Data Analysis for Ames Housing :house_with_garden:
Exploratory Data Analyze for Ames Housing dataset from kaggle competition using R programming Language. 

[*here you can download the cheatsheet*](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

## Introduction
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 

## Technical
Languange : R Programming (filetype: *.Rmd*)

## Content
### Data Fields
- **SalePrice** — the property's sale price in dollars. This is the target variable that you're trying to predict.
- **MSSubClass** — The building class
- **MSZoning** — The general zoning classification
- **LotFrontage** — Linear feet of street connected to property
- **LotArea** — Lot size in square feet
- **Street** — Type of road access
- **Alley** — Type of alley access
- **LotShape** — General shape of property
- **LandContour** — Flatness of the property
- **Utilities** — Type of utilities available
- **LotConfig** — Lot configuration
- **LandSlope** — Slope of property
- **Neighborhood** — Physical locations within Ames city limits
- **Condition1** — Proximity to main road or railroad
- **Condition2** — Proximity to main road or railroad (if a second is present)
- **BldgType** — Type of dwelling
- **HouseStyle** — Style of dwelling
- **OverallQual** — Overall material and finish quality
- **OverallCond** — Overall condition rating
- **YearBuilt** — Original construction date
- **YearRemodAdd** — Remodel date
- **RoofStyle** — Type of roof
- **RoofMatl** — Roof material
- **Exterior1st** — Exterior covering on house
- **Exterior2nd** — Exterior covering on house (if more than one material)
- **MasVnrType** — Masonry veneer type
- **MasVnrArea** — Masonry veneer area in square feet
- **ExterQual** — Exterior material quality
- **ExterCond** — Present condition of the material on the exterior
- **Foundation** — Type of foundation
- **BsmtQual** — Height of the basement
- **BsmtCond** — General condition of the basement
- **BsmtExposure** — Walkout or garden level basement walls
- **BsmtFinType1** — Quality of basement finished area
- **BsmtFinSF1** — Type 1 finished square feet
- **BsmtFinType2** — Quality of second finished area (if present)
- **BsmtFinSF2** — Type 2 finished square feet
- **BsmtUnfSF** — Unfinished square feet of basement area
- **TotalBsmtSF** — Total square feet of basement area
- **Heating** — Type of heating
- **HeatingQC** — Heating quality and condition
- **CentralAir** — Central air conditioning
- **Electrical** — Electrical system
- **1stFlrSF** — First Floor square feet
- **2ndFlrSF** — Second floor square feet
- **LowQualFinSF** — Low quality finished square feet (all floors)
- **GrLivArea** — Above grade (ground) living area square feet
- **BsmtFullBath** — Basement full bathrooms
- **BsmtHalfBath** — Basement half bathrooms
- **FullBath** — Full bathrooms above grade
- **HalfBath** — Half baths above grade
- **Bedroom** — Number of bedrooms above basement level
- **Kitchen** — Number of kitchens
- **KitchenQual** — Kitchen quality
- **TotRmsAbvGrd** — Total rooms above grade (does not include bathrooms)
- **Functional** — Home functionality rating
- **Fireplaces** — Number of fireplaces
- **FireplaceQu** — Fireplace quality
- **GarageType** — Garage location
- **GarageYrBlt** — Year garage was built
- **GarageFinish** — Interior finish of the garage
- **GarageCars** — Size of garage in car capacity
- **GarageArea** — Size of garage in square feet
- **GarageCond — Garage condition
- **PavedDrive** — Paved driveway
- **WoodDeckSF** — Wood deck area in square feet
- **OpenPorchSF** — Open porch area in square feet
- **EnclosedPorch** — Enclosed porch area in square feet
- **3SsnPorch** — Three season porch area in square feet
- **ScreenPorch** — Screen porch area in square feet
- **PoolArea** — Pool area in square feet
- **PoolQC** — Pool quality
- **Fence** — Fence quality
- **MiscFeature** — Miscellaneous feature not covered in other categories
- **MiscVal** — $Value of miscellaneous feature
- **MoSold** — Month Sold
- **YrSold** — Year Sold
- **SaleType** — Type of sale
- **SaleCondition** — Condition of sale

## Question Inside the Program

1. *Start with the target.* Lakukan analisis univariat terhadap variabel target, yakni SalePrice dan deskripsikan apa saja insight yang bisa didapat.
2. Cari 5 variabel dengan korelasi paling kuat(secara positive ataupun negative) terhadap SalePrice, dan kira-kira apakah hasilnya masuk akal?
3. *It is never hurt to test basic knowledge.* Ada pandangan bahwa OverallQual rendah memiliki kecenderungan harga yang lebih rendah, dan rumah dengan OverallQual memiliki kecenderungan harga yang lebih tinggi. Lakukan analisis terhaadp hubungan OverallQual dan SalePrice.
4. *Beware of false correlation.* Ada kecenderungan bahwa rumah baru memiliki harga yang lebih tinggi. Akan tetapi, kita tidak boleh gegabah untuk menyimpulkan bahwa rumah baru pasti memiliki harga jual yang lebih tinggi, karena apabila rumah baru yang dibangun tidak baik, tentu harganya juga tidak bisa tinggi. Kira-kira apa hal yang membuat rumah baru memiliki nilai yang lebih tinggi? *Hint : Cek korelasi antara YearBuilt dengan prediktor lainnya*
5. Haunted place(?) Perhatikan scatter plot berikut <code> df %>% ggplot(aes(x=GrLivArea,y=SalePrice)) + geom_point()</code> . Disebelah kanan, ada dua rumah, yang memiliki GreenLivingArea sangat besar, tetapi SalePrice nya murah. Coba analisis kenapa kedua rumah tersebut murah.
6. Lakukan EDA secara bebas dan sampaikan 1 insight yang sekiranya menarik.

## [Click Here  for Visualize and Analyze](https://arienugroho050396.github.io/project2.html) :thumbsup: :thumbsup: :thumbsup:  
