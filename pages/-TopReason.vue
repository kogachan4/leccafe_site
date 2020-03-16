<template>
    <div class="p-top__reason">
        <h1 class="p-top__titles c-textRed">Reason</h1>
        <div class="flex">
            <div class="p-top_reason__point01 col-sm-6">
                <img class="p-top_reason__image" src="~/assets/images/top_img1.jpg" alt="">
                <div class="p-top_reason__box">
                    <h3>現場で使える技術を</h3>
                    <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                </div>
            </div>
            <div class="p-top_reason__point02 col-sm-6">
                <img class="p-top_reason__image" src="~/assets/images/top_img1.jpg" alt="">
                <div class="p-top_reason__box">
                    <h3>個別カリキュラム</h3>
                    <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                </div>
            </div>
        </div>
        <div class="flex">
            <div class="p-top_reason__point03 col-sm-6">
                <img class="p-top_reason__image" src="~/assets/images/top_img1.jpg" alt="">
                <div class="p-top_reason__box">
                    <h3>自分で学べる学習スタイル</h3>
                    <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                </div>
            </div>
            <div class="p-top_reason__point04 col-sm-6">
                <img class="p-top_reason__image" src="~/assets/images/top_img1.jpg" alt="">
                <div class="p-top_reason__box">
                    <h3>縛りなしで１ヶ月ごとの契約</h3>
                    <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    .p-top__titles {
        padding-top: 50px;
    }
    .p-top__reason {
        background-color: #FFEDE6;
        text-align: center;
        height: auto;
    }
    .p-top_reason__image {
        width: 120px;
        height: 120px;
    }
    .p-top_reason__box {
        background-color: #ffffff;
        margin-left: 80px;
        width: 310px;
        padding: 16px;
    }
    .p-top_reason__point01 {
        // margin-left: 400px;
        // width: 310px;
        margin-bottom: 40px;
    }
    .p-top_reason__point02 {
        // width: 310px;
    }
    .p-top_reason__point03 {
        // margin-left: 400px;
        // width: 310px;
        margin-bottom: 80px;
    }
    .p-top_reason__point04 {
        width: 310px;
    }
    .flex {
        display: flex;
    }
</style>