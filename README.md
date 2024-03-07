# House-Prices---Advanced-Regression-Techniques
Predict sales prices and practice feature engineering, RFs, and gradient boosting
<Br><Br>
Dataset Description
File descriptions <Br>
train.csv - the training set<Br>
test.csv - the test set<Br>
data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here<Br>
sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms<Br>
Data fields<Br>
Here's a brief version of what you'll find in the data description file.<Br>
<Br><Br>
SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.<Br>
MSSubClass: The building class<Br>
MSZoning: The general zoning classification<Br>
LotFrontage: Linear feet of street connected to property<Br>
LotArea: Lot size in square feet<Br>
Street: Type of road access<Br>
Alley: Type of alley access<Br>
LotShape: General shape of property<Br>
LandContour: Flatness of the property<Br>
Utilities: Type of utilities available<Br>
LotConfig: Lot configuration<Br>
LandSlope: Slope of property<Br>
Neighborhood: Physical locations within Ames city limits<Br>
Condition1: Proximity to main road or railroad<Br>
Condition2: Proximity to main road or railroad (if a second is present)<Br>
BldgType: Type of dwelling<Br>
HouseStyle: Style of dwelling<Br>
OverallQual: Overall material and finish quality<Br>
OverallCond: Overall condition rating<Br>
YearBuilt: Original construction date<Br>
YearRemodAdd: Remodel date<Br>
RoofStyle: Type of roof<Br>
RoofMatl: Roof material<Br>
Exterior1st: Exterior covering on house<Br>
Exterior2nd: Exterior covering on house (if more than one material)<Br>
MasVnrType: Masonry veneer type<Br>
MasVnrArea: Masonry veneer area in square feet<Br>
ExterQual: Exterior material quality<Br>
ExterCond: Present condition of the material on the exterior<Br>
Foundation: Type of foundation<Br>
BsmtQual: Height of the basement<Br>
BsmtCond: General condition of the basement<Br>
BsmtExposure: Walkout or garden level basement walls<Br>
BsmtFinType1: Quality of basement finished area<Br>
BsmtFinSF1: Type 1 finished square feet<Br>
BsmtFinType2: Quality of second finished area (if present)<Br>
BsmtFinSF2: Type 2 finished square feet<Br>
BsmtUnfSF: Unfinished square feet of basement area<Br>
TotalBsmtSF: Total square feet of basement area<Br>
Heating: Type of heating<Br>
HeatingQC: Heating quality and condition<Br>
CentralAir: Central air conditioning<Br>
Electrical: Electrical system<Br>
1stFlrSF: First Floor square feet<Br>
2ndFlrSF: Second floor square feet<Br>
LowQualFinSF: Low quality finished square feet (all floors)<Br>
GrLivArea: Above grade (ground) living area square feet<Br>
BsmtFullBath: Basement full bathrooms<Br>
BsmtHalfBath: Basement half bathrooms<Br>
FullBath: Full bathrooms above grade<Br>
HalfBath: Half baths above grade<Br>
Bedroom: Number of bedrooms above basement level<Br>
Kitchen: Number of kitchens<Br>
KitchenQual: Kitchen quality<Br>
TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)<Br>
Functional: Home functionality rating<Br>
Fireplaces: Number of fireplaces<Br>
FireplaceQu: Fireplace quality<Br>
GarageType: Garage location<Br>
GarageYrBlt: Year garage was built<Br>
GarageFinish: Interior finish of the garage<Br>
GarageCars: Size of garage in car capacity<Br>
GarageArea: Size of garage in square feet<Br>
GarageQual: Garage quality<Br>
GarageCond: Garage condition<Br>
PavedDrive: Paved driveway<Br>
WoodDeckSF: Wood deck area in square feet<Br>
OpenPorchSF: Open porch area in square feet<Br>
EnclosedPorch: Enclosed porch area in square feet<Br>
3SsnPorch: Three season porch area in square feet<Br>
ScreenPorch: Screen porch area in square feet<Br>
PoolArea: Pool area in square feet<Br>
PoolQC: Pool quality<Br>
Fence: Fence quality<Br>
MiscFeature: Miscellaneous feature not covered in other categories<Br>
MiscVal: $Value of miscellaneous feature<Br>
MoSold: Month Sold<Br>
YrSold: Year Sold<Br>
SaleType: Type of sale<Br>
SaleCondition: Condition of sale<Br>
