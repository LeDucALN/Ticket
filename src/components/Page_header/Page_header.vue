<script setup lang="ts">

</script>

<template>
  <div id="page-header">
    <div id="Frame157">
        <div id="menu-fold">
            <svg width="10" height="10" viewBox="0 0 10 10" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M5.79297 9.80099L2.4082 5.30099C2.34329 5.21444 2.30859 5.10913 2.30859 5.00094C2.30859 4.89276 2.34329 4.78744 2.4082 4.70089L5.79297 0.200892C5.83237 0.148364 5.88295 0.104219 5.93945 0.0707654C5.99595 0.0373116 6.05805 0.015354 6.12305 0.00606813C6.18805 -0.00321773 6.2528 0.000270383 6.31641 0.0165662C6.38001 0.032862 6.44161 0.0616423 6.49414 0.101039L7.30078 0.707972C7.40512 0.788801 7.47352 0.907152 7.49219 1.03781C7.51085 1.16846 7.47792 1.30111 7.40039 1.40792L4.70117 4.99606L7.40039 8.58395C7.44134 8.63676 7.47111 8.69735 7.48828 8.76193C7.50546 8.82651 7.5093 8.89375 7.5 8.95993C7.49158 9.02455 7.4703 9.08696 7.4375 9.14328C7.4047 9.1996 7.36064 9.24883 7.30859 9.28805L6.50195 9.89498C6.41579 9.96062 6.31144 9.99565 6.20312 9.99484C6.1245 9.99695 6.04568 9.98069 5.97461 9.94699C5.90354 9.91328 5.84108 9.86322 5.79297 9.80099Z" fill="white" fill-opacity="0.7"/>
            </svg>
            <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M2.5 3C2.22386 3 2 3.22386 2 3.5V4.5C2 4.77614 2.22386 5 2.5 5H17.5C17.7761 5 18 4.77614 18 4.5V3.5C18 3.22386 17.7761 3 17.5 3H2.5Z" fill="white" fill-opacity="0.7"/>
                <path d="M2.5 9C2.22386 9 2 9.22386 2 9.5V10.5C2 10.7761 2.22386 11 2.5 11H17.5C17.7761 11 18 10.7761 18 10.5V9.5C18 9.22386 17.7761 9 17.5 9H2.5Z" fill="white" fill-opacity="0.7"/>
                <path d="M2.5 15C2.22386 15 2 15.2239 2 15.5V16.5C2 16.7761 2.22386 17 2.5 17H11.5C11.7761 17 12 16.7761 12 16.5V15.5C12 15.2239 11.7761 15 11.5 15H2.5Z" fill="white" fill-opacity="0.7"/>
            </svg>
        </div>
    </div>
    <div id="Frame12">
        <div id="avatar"></div>
        <div id="username">LeMinhDuc</div>
    </div>
  </div>
</template> 

<style scoped lang="scss">
@use '../../assets/base';
#page-header {
    @include base.layout(100%, 40px, 0, 8px);
    justify-content: space-between;
    // padding: 12px;
    background-color: #DE2233;
    align-self: stretch;

    #Frame157 {
            #menu-fold {
            @include base.layout(50px, 40px, 0, 4px);
            justify-content: center;
            padding: 10px 8px;
            border-radius: 8px;
            }
    }
}



#Frame12 {
    @include base.layout(202px,32px,2,16px);
    padding: 0px;
    #avatar {
        width: 32px;
        height: 32px;
        background: #FFFFFF;
        border-radius: 99px;
        flex: none;
        order: 0;
        flex-grow: 0;
    }
    #username {
        width: 154px;
        height: 21px;
        font-family: Roboto;
        font-style: normal;
        font-weight: 300;
        font-size: 14px;
        line-height: 21px;
        color: #FFFFFF;
        flex: none;
        order: 1;
        flex-grow: 0;
    }

}

</style>