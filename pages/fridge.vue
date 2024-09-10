<template>
    <div class="page ph7">
        <sub-header :title="'fridge'" />
        <div></div>
        <div>
            <div class="text-center">
                <div class="mb7">
                    <p>browse the fridge</p>
                </div>
                <div class="flex flex-row margin-a fridge">
                    <div class="flex flex-col w-33">
                        <div>
                            <p>drinks</p>
                        </div>
                        <div>
                            <p>dairy</p>
                        </div>
                        <div>
                            <p>condiments</p>
                        </div>
                    </div>
                    <div class="flex flex-col w-33">
                        <div>
                            <p>produce</p>
                        </div>
                        <div>
                            <p>desserts</p>
                        </div>
                        <div>
                            <p>frozen</p>
                        </div>
                    </div>
                    <div class="flex flex-col w-33">
                        <div>
                            <p>proteins</p>
                        </div>
                        <div>
                            <p>leftovers</p>
                        </div>
                        <div>
                            <p>misc</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>