<template>
    <nav>
        <router-link to="/login">
            <svg t="1650613501507"
                 class="icon"
                 viewBox="0 0 1024 1024" version="1.1"
                 xmlns="http://www.w3.org/2000/svg"
                 p-id="4471"
                 width="20"
                 height="20">
                <path d="M902.779659 795.440467c-6.179746-6.181793-14.304797-9.577123-22.950711-9.577123L129.341299 785.863345c-17.945721 0-32.540114 14.59644-32.540114 32.525788 0 17.962094 14.594393 32.555463 32.540114 32.555463l750.487649 0c17.931395 0 32.525788-14.594393 32.525788-32.555463C912.354735 809.745265 908.959406 801.61919 902.779659 795.440467"
                      p-id="4472"></path>
                <path d="M879.828948 461.055724 129.341299 461.055724c-17.945721 0-32.525788 14.594393-32.525788 32.541137 0 17.930371 14.580067 32.525788 32.525788 32.525788l750.487649 0c17.931395 0 32.525788-14.594393 32.525788-32.525788 0-8.647961-3.39533-16.800641-9.575076-22.980387C896.599913 464.436728 888.474862 461.055724 879.828948 461.055724"
                      p-id="4473"></path>
                <path d="M902.779659 154.426115c-6.179746-6.179746-14.304797-9.574053-22.950711-9.574053L129.341299 144.852062c-17.945721 0-32.540114 14.594393-32.540114 32.540114 0 17.946744 14.594393 32.525788 32.540114 32.525788l750.487649 0c17.931395 0 32.525788-14.579043 32.525788-32.525788C912.354735 168.745239 908.959406 160.606885 902.779659 154.426115"
                      p-id="4474"></path>
            </svg>
        </router-link>

        <div>
            <router-link to="/profile">我的</router-link>
            <router-link to="/">发现</router-link>
            <router-link to="/yun-cun">云村</router-link>
            <router-link to="/video">视频</router-link>
        </div>

        <router-link to="/search">
            <svg t="1650613145271"
                 class="icon"
                 viewBox="0 0 1024 1024"
                 version="1.1"
                 xmlns="http://www.w3.org/2000/svg"
                 p-id="2159"
                 width="20"
                 height="20">
                <path d="M934.242232 884.637975 738.287281 695.561689l1.836835-2.302439c52.767807-65.338101 81.829703-147.602709 81.829703-231.593636 0-203.716728-165.742858-369.473913-369.411491-369.473913-203.731054 0-369.505635 165.757185-369.505635 369.473913 0 203.715705 165.774581 369.45754 369.505635 369.45754 89.26607 0 175.511339-32.450063 242.841817-91.288123l2.209318-1.929955 195.485253 186.963159 1.959631 0 0.031722 1.61887c4.947685 3.483334 10.517541 5.319146 16.5837 5.319146 16.180518 0 29.308513-13.192464 29.308513-29.310559C940.96126 896.276037 938.72329 890.239554 934.242232 884.637975zM452.541305 772.413008c-171.358763 0-310.74637-139.388631-310.74637-310.74637 0-171.34239 139.387607-310.700321 310.74637-310.700321 171.309644 0 310.700321 139.357931 310.700321 310.700321C763.241626 633.024377 623.851972 772.413008 452.541305 772.413008z"
                      p-id="2160"></path>
            </svg>
        </router-link>
    </nav>
</template>

<script>
    export default {
        name: "HeaderCom"
    }
</script>

<style scoped lang="less">
    nav {
        display: flex;
        justify-content: space-between;
        margin-bottom: 10px;

        div {
            width: 200px;
            display: flex;
            justify-content: space-between;

            a {
                color: #000;
                text-decoration: none;
            }
            .router-link-active{
                font-weight: bold;
            }
        }
    }


</style>