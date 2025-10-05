<template>
    <nav class="navbar navbar-expand-lg navbar-light py-4 border-bottom">
        <div class="container col-md-12">
            <a class="navbar-brand" href="#">Open Dealz</a>
        </div>
    </nav>

    <div class="container col-md-12">
        <div class="row">
            <div class="col-md-8 mt-5">
                <div class="position-relative">
                    <i class="bi bi-search position-absolute top-50 start-0 translate-middle-y ms-3 text-muted"></i>
                    <input class="search-input form-control form-control-sm ps-5 bg-white border-0"
                        placeholder="판매자 프로필 또는 태그로 검색해보세요." value="">
                </div>
            </div>
        </div>
        <div class="container card-deck">
            <div class="row col-md-4 card-profiles">
                <div class="card overflow-hidden mt-5 shadow-sm border-0">
                    <div class="card-header bg-white border-0 d-flex align-items-center" style="height: 64px;">
                        <img src="" alt="Profile" class="rounded-circle me-2"
                            style="width: 40px; height: 40px; object-fit: cover;">
                        <span>profile_name</span>
                    </div>
                    <div class="card-body p-0">
                        <img src="" class="card-body-img w-100 rounded-0"
                            alt="">
                    </div>
                    <div class="card-footer bg-white border-0 d-flex justify-content-between align-items-center"
                        style="height: 64px;"></div>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
.search-input::placeholder {
    font-size: 0.75rem;
    color: #aaa;
}

.card-profiles {
    height: 40rem;
    border-radius: 20rem;
}

.card-profiles .card {
    width: 100%;
}

.card-body-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
</style>