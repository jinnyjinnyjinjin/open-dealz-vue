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
        <div class="row mt-5">
            <div class="card-contianer col-md-3 mb-4 p-0">
                <div class="card-header bg-white border-0 d-flex align-items-center">
                    <img src="" alt="Profile" class="rounded-circle me-2">
                    <span>profile_name</span>
                </div>
                <div class="card-body">
                    <img src="" class="w-100 rounded-0" alt="">
                </div>
                <div class="card-footer bg-white border-0 d-flex justify-content-between align-items-center"></div>
            </div>
        </div>
    </div>
</template>

<style>
.search-input::placeholder {
    font-size: 0.75rem;
    color: #aaa;
}

.card-contianer {
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    background-color: #fff;
    height: 600px;
    display: flex;
    flex-direction: column;
}

.card-header {
    height: 64px;
}

.card-header img {
    width: 40px;
    height: 40px;
    object-fit: cover
}

.card-body {
    flex: 1;
    height: 500px;
    overflow: hidden;
}

.card-body img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.card-footer {
    height: 64px;
}
</style>