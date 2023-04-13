<script setup lang="ts">
import Input from '../../../Input/Input.vue'
</script>
<template>
    <div id="search">
            <div id="Frame14">
                <div id="Frame28">
                    <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M7.57301 2.66668L7.83967 4.00001H13.333V10.6667H9.17567L8.90901 9.33334H2.66634V2.66668H7.57301ZM8.39301 1.33334H1.66634C1.57794 1.33334 1.49315 1.36846 1.43064 1.43097C1.36813 1.49349 1.33301 1.57827 1.33301 1.66668V14.3333C1.33301 14.4217 1.36813 14.5065 1.43064 14.569C1.49315 14.6316 1.57794 14.6667 1.66634 14.6667H2.33301C2.42141 14.6667 2.5062 14.6316 2.56871 14.569C2.63122 14.5065 2.66634 14.4217 2.66634 14.3333V10.6667H7.81567L8.02901 11.7333C8.04438 11.8086 8.08529 11.8763 8.14481 11.9249C8.20434 11.9735 8.27883 12 8.35567 12H14.333C14.4214 12 14.5062 11.9649 14.5687 11.9024C14.6312 11.8399 14.6663 11.7551 14.6663 11.6667V3.00001C14.6663 2.9116 14.6312 2.82682 14.5687 2.76431C14.5062 2.7018 14.4214 2.66668 14.333 2.66668H8.93301L8.71967 1.60001C8.70431 1.52472 8.6634 1.45705 8.60387 1.40846C8.54434 1.35986 8.46985 1.33333 8.39301 1.33334Z" fill="#202529"/>
                        <path d="M11.9993 10.8971V10.6667H10.666V9.33334H9.33268V8.00001H8.63867L8.37174 6.66668H9.33268V8.00001H10.666V9.33334H11.9993V10.6667H13.3327V10.8971H11.9993ZM9.33268 10.8971V10.6667H9.17122L8.9056 9.33334H9.33398V10.6667H10.6673V10.8971H9.33268ZM11.9993 9.33334V7.99936L10.666 8.00001V6.66603L9.33268 6.66668V5.33269H8.10482L7.99805 4.8034V4.00327H9.33138V5.3366H10.6647V6.66993H11.998V8.00327H13.3314V9.3366L11.9993 9.33334ZM11.9993 6.66603V5.33269H10.666V3.99936H11.9993V5.33269H13.3327V6.66603H11.9993Z" fill="#202529"/>
                        <path d="M8.9069 9.33335H7.99935V8.00002H8.64258L8.9095 9.33335H8.9069ZM6.66602 9.33335H5.33268V8.00002H6.66602V9.33335ZM3.99935 9.33335H2.66602V8.00002H3.99935V9.33335ZM7.99935 8.00002H6.66602V6.66669H7.99935V8.00002ZM5.33268 8.00002H3.99935V6.66669H5.33268V8.00002ZM6.66602 6.66669H5.33268V5.33335H6.66602V6.66669ZM3.99935 6.66669H2.66602V5.33335H3.99935V6.66669ZM8.37695 6.66669H7.99935V5.33335H8.11003L8.37695 6.66669ZM7.99935 5.33335H6.66602V4.00002H7.83919L7.99805 4.78322V5.33466L7.99935 5.33335ZM5.33268 5.33335H3.99935V4.00002H5.33268V5.33335ZM6.66602 4.00002H5.33268V2.66669H6.66602V4.00002ZM3.99935 4.00002H2.66602V2.66669H3.99935V4.00002Z" fill="#202529"/>
                    </svg>
                    <div id="info-race">レース情報</div>
                </div>
                <div id="Frame29">
                    <svg width="10" height="10" viewBox="0 0 10 10" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M4.62176 1.74699C4.66991 1.69443 4.72848 1.65246 4.79372 1.62374C4.85897 1.59503 4.92948 1.5802 5.00076 1.5802C5.07205 1.5802 5.14255 1.59503 5.2078 1.62374C5.27305 1.65246 5.33161 1.69443 5.37976 1.74699L9.86476 6.63999C9.93207 6.71355 9.97654 6.80509 9.99274 6.90347C10.0089 7.00185 9.99618 7.10282 9.95601 7.19407C9.91584 7.28533 9.85 7.36293 9.7665 7.41742C9.68301 7.47192 9.58547 7.50095 9.48576 7.50099L0.515761 7.50099C0.416056 7.50095 0.318514 7.47192 0.23502 7.41742C0.151525 7.36293 0.0856826 7.28533 0.0455135 7.19407C0.00534434 7.10282 -0.00741692 7.00185 0.00878443 6.90347C0.0249858 6.80509 0.0694503 6.71354 0.136761 6.63999L4.62176 1.74699Z" fill="#DE2233"/>
                    </svg>
                </div>
            </div>
            <div id="Frame37">
                <div id="Frame18">
                    <div id="Frame17">
                        <div id="STT">
                            レースID
                        </div>
                        <Input place="12345678"/>
                    </div>
                    <div id="Frame16">
                        <div id="name">
                            レース名
                        </div>
                        <Input place="SUPER GT"/>
                    </div>
                </div>
                <div id="Frame19">
                    <div id="stage">
                            開催期間
                    </div>
                    <div id="Frame15">
                        <Input :flexgrows="0" :width="'40%'" place="2022/05/03(水) ~"/>
                        <Input :flexgrows="0" :width="'50%'" place="2022/05/04(水)"/>  
                </div>
            </div>
        </div>
    </div>
    
</template>


<style scoped lang="scss">
    #search {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        padding: 10px 16px;
        gap: 8px;
        isolation: isolate;
        width: 100%;
        height: 104px;
        background: #FFFFFF;
        box-shadow: 0px 4px 16px rgba(0,0,0,0.05);
        border-radius: 8px;
        #Frame14 {
            display: flex;
            flex-direction: row;
            align-items: center;
            justify-content: space-between;
            padding: 0px;
            gap: 8px;
            width: 100%;
            height: 24px;
            flex: none;
            order: 0;
            align-self: stretch;
            flex-grow: 0;
            z-index: 0;
            #Frame28 {
                display: flex;
                flex-direction: row;
                align-items: center;
                padding: 0px;
                gap: 8px;
                width: 103px;
                height: 24px;
                flex: none;
                order: 0;
                flex-grow: 0;
                #info-race {
                    width: 80px;
                    height: 24px;
                    font-style: normal;
                    font-weight: 600;
                    font-size: 16px;
                    line-height: 24px;
                    color: #202529;
                    flex: none;
                    order: 1;
                    flex-grow: 0;
                }
            }
        }
        #Frame37 {
            display: flex;
            flex-direction: row;
            align-items: flex-start;
            padding: 0px;
            gap: 16px;
            width: 100%;
            height: 52px;
            flex: none;
            order: 1;
            align-self: stretch;
            flex-grow: 0;
            z-index: 1;
            #Frame18 {
                display: flex;
                flex-direction: row;
                align-items: flex-start;
                padding: 0px;
                gap: 16px;
                width: 50%;
                height: 52px;
                flex: none;
                order: 0;
                flex-grow: 1;
                #Frame17 {
                    display: flex;
                    flex-direction: column;
                    align-items: flex-start;
                    padding: 0px;
                    // width: 258px;
                    height: 52px;
                    flex: none;
                    order: 0;
                    flex-grow: 1;
                    #STT {
                        font-style: normal;
                        font-weight: 600;
                        font-size: 14px;
                        line-height: 20px;
                        // width: 60px;
                        height: 20px;
                        color: #87898B;
                        flex: none;
                        order: 1;
                        flex-grow: 0;
                    }
                    
                }
                #Frame16 {
                    display: flex;
                    flex-direction: column;
                    align-items: flex-start;
                    padding: 0px;
                    // width: 258px;
                    height: 52px;
                    flex: none;
                    order: 1;
                    flex-grow: 1;
                    #name {
                        // width: 60px;
                        font-family: 'Hiragino Kaku Gothic ProN';
                        height: 20px;
                        font-style: normal;
                        font-weight: 600;
                        font-size: 14px;
                        line-height: 20px;
                        color: #87898B;
                        flex:none;
                        order: 2;
                        flex-grow: 0;
                }
            }
            
            }
            #Frame19 {
                display: flex;
                flex-direction: column;
                align-items: flex-start;
                padding: 0px;
                width: 50%;
                height: 52px;
                flex: none;
                order: 1;
                flex-grow: 1;
                #stage {
                    display: flex;
                    flex-direction: row;
                    align-items: center;
                    padding: 0px;
                    gap: 6px;
                    width: 100%;
                    height: 20px;
                    border-radius: 4px;
                    flex:none;
                    order: 0;
                    align-self: stretch;
                    flex-grow: 0;
                }
                #Frame15 {
                    display: flex;
                    flex-direction: row;
                    align-items: flex-start;
                    padding: 0px;
                    gap: 12px;
                    width: 100%;
                    height: 32px;
                    flex: none;
                    order: 1;
                    align-self: stretch;
                    flex-grow: 0;
                }
            }
        }
    }
</style>