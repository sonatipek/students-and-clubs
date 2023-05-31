<template>

    <div class="col-xxl-8 px-4 py-5 w-100">
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
            <div class="col-10 col-sm-8 col-lg-6">
                <img src="/illustrates/grup.svg" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="75%" loading="lazy">
            </div>
            <div class="col-lg-6">
                <h1 class="display-5 fw-medium text-dark mb-3">{{ title }}</h1>
                <p class="fw-normal text-secondary">{{ desc }}</p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                    <a href="/ogrenciler" class="btn btn-primary btn-lg px-4 me-md-2">{{ primary_button }}</a>
                    <a href="/topluluklar" class="btn btn-outline-primary btn-lg px-4">{{ secondary_button }}</a>
                </div>
            </div>
        </div>
    </div>

</template>

<script>
    export default{
        name: "Header",
        data() {
            return{
                title: 'Öğrencileri Bulun',
                desc: 'lorem ipsum dolor sit amet',
                primary_button: 'Kayıtlı Öğrenciler',
                secondary_button: 'Kayıtlı Topluluklar',
            }
        },
    }
</script>