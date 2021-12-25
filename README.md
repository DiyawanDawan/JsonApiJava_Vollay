# JsonApiJava_Vollay
App Android Java with Json Api

Jangan lupa tambahkan dependencies volly dan glide di "buildgralde module app" , supaya bisa menapilan Json Api yanng berbentuk RequestQueue volly dan juga glide untuk menapilkan image


    dependencies {
        implementation 'com.android.volley:volley:1.1.1
        implementation 'com.github.bumptech.glide:glide:4.12.0'
        annotationProcessor 'com.github.bumptech.glide:compiler:4.12.0'
    }

Tambakna Juga Android permissen Interet di AndroidManifaset

    <uses-permission android:name="android.permission.INTERNET"/>

Calass DataALgoritma

    public DataALgoritma(String nameAlgoritma, String baca_lebih_lanjut, String description, String logo) {
        this.nameAlgoritma = nameAlgoritma;
        this.baca_lebih_lanjut = baca_lebih_lanjut;
        this.description = description;
        this.logo = logo;
    }

    public String getNameAlgoritma() {
        return nameAlgoritma;
    }

    public String getBaca_lebih_lanjut() {
        return baca_lebih_lanjut;
    }

    public String getDescription() {
        return description;
    }

    public String getLogo() {
        return logo;
    }
}



Dokumentasi detail tentang dependencies vollay https://developer.android.com/training/volley/

Dekumentasi detail tentang glide https://iqcode.com/code/java/glide

https://user-images.githubusercontent.com/95010003/147268099-c4203b2b-f1f9-4601-9487-b8982382348b.mp4

