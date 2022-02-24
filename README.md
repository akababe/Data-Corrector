# Data-Corrector

Project data-corrector merupakan project sederhana untuk melakukan koreksi data yang tidak seusai dengan.

Background : penarikan data yang dilakukan oleh kontroller terkadang menghasilkan data selisih antara totalizer dan penarikan data harian,
ada beberapa faktor yang mungkin terjadi diantaranyya koneksi yang buruk, interfensi jalur data oleh mesin yang menghasilkan frekunsi harmonic,
environtmet yang terlalu panas atau masalah teknis lainnya sehingga menyebabkan transfer data dari kontroller ke server terganggu.

nilai yang seharusnya (kwh_perhari) = totalizer_sekarang - totalizer_kemarin

Program yang ada di dalam ini melakukan modifikasi terhadap data kwh_perhari apabila ditemukan data yang kurang sesuai
