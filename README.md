Basic Scraper for ENCODE

--> Isolate pertinent samples/cell-lines
--> Extract BigWigs for epigenomic analyses

CONDA ENV

# Name                    Version                   Build  Channel
appnope                   0.1.2           py39hecd8cb5_1001  
asttokens                 2.0.5              pyhd3eb1b0_0  
attrs                     24.2.0           py39hecd8cb5_0  
backcall                  0.2.0              pyhd3eb1b0_0  
beautifulsoup4            4.12.3           py39hecd8cb5_0  
blas                      1.0                         mkl  
bottleneck                1.4.2            py39hf3fd67a_0  
brotli                    1.0.9                h6c40b1e_8  
brotli-bin                1.0.9                h6c40b1e_8  
brotli-python             1.0.9            py39hcec6c5f_8  
ca-certificates           2024.11.26           hecd8cb5_0  
certifi                   2024.8.30        py39hecd8cb5_0  
charset-normalizer        3.3.2              pyhd3eb1b0_0  
comm                      0.2.1            py39hecd8cb5_0  
contourpy                 1.2.0            py39ha357a0b_0  
cycler                    0.11.0             pyhd3eb1b0_0  
debugpy                   1.6.7            py39hcec6c5f_0  
decorator                 5.1.1              pyhd3eb1b0_0  
exceptiongroup            1.2.0            py39hecd8cb5_0  
executing                 0.8.3              pyhd3eb1b0_0  
fonttools                 4.51.0           py39h6c40b1e_0  
freetype                  2.12.1               hd8bbffd_0  
h11                       0.14.0           py39hecd8cb5_0  
icu                       73.1                 hcec6c5f_0  
idna                      3.7              py39hecd8cb5_0  
importlib-metadata        8.5.0            py39hecd8cb5_0  
importlib_metadata        8.5.0                hd3eb1b0_0  
importlib_resources       6.4.0            py39hecd8cb5_0  
intel-openmp              2023.1.0         ha357a0b_43548  
ipykernel                 6.29.5           py39hecd8cb5_0  
ipython                   8.15.0           py39hecd8cb5_0  
jedi                      0.19.1           py39hecd8cb5_0  
jpeg                      9e                   h46256e1_3  
jupyter_client            8.6.0            py39hecd8cb5_0  
jupyter_core              5.7.2            py39hecd8cb5_0  
kiwisolver                1.4.4            py39hcec6c5f_0  
lcms2                     2.12                 hf1fd2bf_0  
lerc                      3.0                  he9d5cce_0  
libbrotlicommon           1.0.9                h6c40b1e_8  
libbrotlidec              1.0.9                h6c40b1e_8  
libbrotlienc              1.0.9                h6c40b1e_8  
libcxx                    14.0.6               h9765a3e_0  
libdeflate                1.17                 hb664fd8_1  
libffi                    3.3                  hb1e8313_2  
libiconv                  1.16                 h6c40b1e_3  
libpng                    1.6.39               h6c40b1e_0  
libsodium                 1.0.18               h1de35cc_0  
libtiff                   4.5.1                hcec6c5f_0  
libwebp-base              1.3.2                h46256e1_1  
libxml2                   2.13.5               h6070cd6_0  
libxslt                   1.1.41               ha190046_0  
lxml                      5.3.0            py39h8defbaf_0  
lz4-c                     1.9.4                hcec6c5f_1  
matplotlib                3.9.2            py39hecd8cb5_1  
matplotlib-base           3.9.2            py39h919b35b_1  
matplotlib-inline         0.1.6            py39hecd8cb5_0  
mkl                       2023.1.0         h8e150cf_43560  
mkl-service               2.4.0            py39h6c40b1e_1  
mkl_fft                   1.3.8            py39h6c40b1e_0  
mkl_random                1.2.4            py39ha357a0b_0  
ncurses                   6.4                  hcec6c5f_0  
nest-asyncio              1.6.0            py39hecd8cb5_0  
numexpr                   2.8.7            py39h827a554_0  
numpy                     1.26.4           py39h827a554_0  
numpy-base                1.26.4           py39ha186be2_0  
openjpeg                  2.5.2                hbf2204d_0  
openssl                   1.1.1w               hca72f7f_0  
outcome                   1.1.0              pyhd3eb1b0_0  
packaging                 24.1             py39hecd8cb5_0  
pandas                    2.2.3            py39h6d0c2b6_0  
parso                     0.8.3              pyhd3eb1b0_0  
pexpect                   4.8.0              pyhd3eb1b0_3  
pickleshare               0.7.5           pyhd3eb1b0_1003  
pillow                    11.0.0           py39h9c91434_0  
pip                       24.2             py39hecd8cb5_0  
platformdirs              3.10.0           py39hecd8cb5_0  
prompt-toolkit            3.0.43           py39hecd8cb5_0  
psutil                    5.9.0            py39hca72f7f_0  
ptyprocess                0.7.0              pyhd3eb1b0_2  
pure_eval                 0.2.2              pyhd3eb1b0_0  
pygments                  2.15.1           py39hecd8cb5_1  
pyparsing                 3.2.0            py39hecd8cb5_0  
pysocks                   1.7.1            py39hecd8cb5_0  
python                    3.9.12               hdfd78df_1  
python-dateutil           2.9.0post0       py39hecd8cb5_2  
python-tzdata             2023.3             pyhd3eb1b0_0  
pytz                      2024.1           py39hecd8cb5_0  
pyzmq                     25.1.2           py39hcec6c5f_0  
readline                  8.2                  hca72f7f_0  
requests                  2.32.3           py39hecd8cb5_1  
selenium                  4.24.0           py39hcc58cb1_0  
setuptools                75.1.0           py39hecd8cb5_0  
six                       1.16.0             pyhd3eb1b0_1  
sniffio                   1.3.0            py39hecd8cb5_0  
sortedcontainers          2.4.0              pyhd3eb1b0_0  
soupsieve                 2.5              py39hecd8cb5_0  
sqlite                    3.45.3               h6c40b1e_0  
stack_data                0.2.0              pyhd3eb1b0_0  
tbb                       2021.8.0             ha357a0b_0  
tk                        8.6.14               h4d00af3_0  
tornado                   6.4.1            py39h46256e1_0  
traitlets                 5.14.3           py39hecd8cb5_0  
trio                      0.26.2           py39hecd8cb5_0  
trio-websocket            0.11.1           py39hecd8cb5_0  
typing_extensions         4.11.0           py39hecd8cb5_0  
tzdata                    2024b                h04d1e81_0  
unicodedata2              15.1.0           py39h6c40b1e_0  
urllib3                   2.2.3            py39hecd8cb5_0  
wcwidth                   0.2.5              pyhd3eb1b0_0  
websocket-client          1.8.0            py39hecd8cb5_0  
wheel                     0.44.0           py39hecd8cb5_0  
wsproto                   1.2.0            py39hecd8cb5_0  
xz                        5.4.6                h6c40b1e_1  
zeromq                    4.3.5                hcec6c5f_0  
zipp                      3.21.0           py39hecd8cb5_0  
zlib                      1.2.13               h4b97444_1  
zstd                      1.5.6                h138b38a_0  
