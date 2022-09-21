<template>
    <div class="frame-788 screen">
        <div class="frame-789">
            <div class="top-text">Are you sure you want to leave the checkout flow?</div>
            <p class="mid-text">You'll lose all progress up until this point.</p>
        </div>
        <div class="frame-790">
            <div class="frame-787">
                <!-- poner botones -->
                <a href="#" class="myButton">Yes, I'll leave</a>
                <a href="#" class="myButton">Cancel</a>
            </div>
        </div>
    </div>
</template>

<style>
    .frame-788 {
        align-items: flex-start;
        background-color: #ffffff;
        border: 1px none;
        display: flex;
        flex-direction: column;
        gap: 24px;
        height: 100vh;
        min-height: 242px;
        max-height: 375px;
        padding: 32px 20px 48px;
        width: 100%;
    }

    .frame-789 {
        align-items: flex-start;
        border: 1px none;
        display:  flex;
        flex-direction: column;
        gap: 12px;
        widows: fit-content;
    }

    .top-text {
        color: var(--black);
        font-family: serif;
        font-size: 20px;
        font-weight: 900;
        letter-spacing: -0.25px;
        line-height: 23px;
        margin-top: -1px;
        width: 335px;
    }

    .mid-text {
        color: #666666;
        font-family: 'Courier New', Courier, monospace;
        font-size: 16px;
        font-weight: 400;
        letter-spacing: 0;
        line-height: 24px;
        white-space: nowrap;
        width: 335px;
    }

    .frame-790 {
        align-items: flex-start;
        border: 1px none;
        display: flex;
        gap: 15px;
        width: fit-content;
    }

    .frame-787 {
        align-items: flex-start;
        border: 1px none;
        display: flex;
        gap: 12px;
        height: 56px;
        width: 335px;
    }

    .myButton {
        box-sizing: border-box;
        background-color:#5500ff;
        border: 2px solid #5700FF;
        border-radius:28px;
        border:1px solid #5500ff;
        display:flex;
        cursor:pointer;
        color:#ffffff;
        font-family:Arial;
        font-size:17px;
        padding:16px 32px;
        text-decoration:none;
        text-shadow:0px 1px 0px #ffffff;
        flex-direction: column;
        align-items: center;
        width: 160px;
        height: 56px;
        flex: none;
        order: 0;
        
        font-size: 16px;
        font-weight: 400;
    }

    .myButton:hover {
	    background-color:#ffffff;
    }
    
    .myButton:active {
	    position:relative;
	    top:1px;
    }

</style>