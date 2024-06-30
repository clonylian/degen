<template>
  <div class="ymain">
    <video autoplay="" loop="" preload="none" muted class="yvideo">
      <source src="../assets/default.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
    <div class="header">
      <div class="headl">
        <a class="headllink" href="/"
          ><svg fill="currentColor" viewBox="0 0 789 668" class="headlsvg">
            <path
              d="M115.185 411.477L118.367 469.444C118.575 473.392 120.055 477.107 122.552 480.15C140.007 501.282 218.264 575.014 394.616 575.014C570.968 575.014 648.278 502.234 666.38 480.544C669.108 477.27 670.68 473.206 670.934 468.933L674.089 411.517C695.084 399.997 716.758 386.98 716.758 386.98C750.835 368.518 788.866 395.038 788.935 433.936C789.051 496.87 739.877 561.545 673.548 602.301C598.758 648.258 487.117 667.324 394.664 667.324C302.211 667.324 190.57 648.258 115.78 602.301C49.4513 561.545 0.277187 496.893 0.392781 433.936C0.462138 395.038 38.4929 368.518 72.5702 386.98C72.5702 386.98 94.207 399.965 115.185 411.477Z"
            ></path>
            <path
              d="M394.641 0.113525C538.834 0.113525 577.929 3.48079 636.558 10.2154H636.535C663.561 13.3272 685.224 33.438 683.212 60.6782L661.616 354.872C654.858 356.83 647.488 359.303 639.223 362.077C595.905 376.615 527.997 399.404 394.64 399.404C261.283 399.404 193.376 376.615 150.057 362.077C141.784 359.3 134.407 356.825 127.643 354.866L106.047 60.6782C104.059 33.438 125.652 12.8395 152.724 10.2154C210.637 4.59548 270.932 0.113525 394.641 0.113525ZM137.991 495.835L138.067 496.869L139.557 497.212C139.024 496.748 138.502 496.289 137.991 495.835ZM649.85 497.178L651.193 496.869L651.262 495.928C650.8 496.341 650.329 496.757 649.85 497.178Z"
            ></path></svg
        ></a>
      </div>
      <div class="headc">
        <button class="headcbut">
          <span>Airdrops</span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 20 20"
            fill="currentColor"
            aria-hidden="true"
            data-slot="icon"
            class="headcsvg"
          >
            <path
              fill-rule="evenodd"
              d="M5.22 8.22a.75.75 0 0 1 1.06 0L10 11.94l3.72-3.72a.75.75 0 1 1 1.06 1.06l-4.25 4.25a.75.75 0 0 1-1.06 0L5.22 9.28a.75.75 0 0 1 0-1.06Z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </button>
        <button class="headcbut">
          <span>Chain</span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 20 20"
            fill="currentColor"
            aria-hidden="true"
            data-slot="icon"
            class="headcsvg"
          >
            <path
              fill-rule="evenodd"
              d="M5.22 8.22a.75.75 0 0 1 1.06 0L10 11.94l3.72-3.72a.75.75 0 1 1 1.06 1.06l-4.25 4.25a.75.75 0 0 1-1.06 0L5.22 9.28a.75.75 0 0 1 0-1.06Z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </button>
        <button class="headcbut">
          <span>Devs</span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 20 20"
            fill="currentColor"
            aria-hidden="true"
            data-slot="icon"
            class="headcsvg"
          >
            <path
              fill-rule="evenodd"
              d="M5.22 8.22a.75.75 0 0 1 1.06 0L10 11.94l3.72-3.72a.75.75 0 1 1 1.06 1.06l-4.25 4.25a.75.75 0 0 1-1.06 0L5.22 9.28a.75.75 0 0 1 0-1.06Z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </button>
        <a href="https://www.degen.tips/tokenomics" class="headca"
          >Tokenomics</a
        >
      </div>
      <div class="headr">
        <button @click="render()" class="headrbut">
          <span>Connect Wallet</span>
          <div class="headrsvgs">
            <svg
              width="16"
              height="16"
              viewBox="0 0 28 28"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M24.0891 3.1199L15.3446 9.61456L16.9617 5.7828L24.0891 3.1199Z"
                fill="#E2761B"
                stroke="#E2761B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M3.90207 3.1199L12.5763 9.67608L11.0383 5.7828L3.90207 3.1199Z"
                fill="#E4761B"
                stroke="#E4761B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M20.9429 18.1745L18.6139 21.7426L23.597 23.1136L25.0295 18.2536L20.9429 18.1745Z"
                fill="#E4761B"
                stroke="#E4761B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M2.97929 18.2536L4.40301 23.1136L9.38607 21.7426L7.05713 18.1745L2.97929 18.2536Z"
                fill="#E4761B"
                stroke="#E4761B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M9.10483 12.1456L7.71626 14.2461L12.6642 14.4658L12.4884 9.14877L9.10483 12.1456Z"
                fill="#E4761B"
                stroke="#E4761B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M18.8864 12.1456L15.4589 9.08725L15.3446 14.4658L20.2837 14.2461L18.8864 12.1456Z"
                fill="#E4761B"
                stroke="#E4761B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M9.38606 21.7426L12.3566 20.2925L9.79033 18.2888L9.38606 21.7426Z"
                fill="#E4761B"
                stroke="#E4761B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M15.6347 20.2925L18.6139 21.7426L18.2009 18.2888L15.6347 20.2925Z"
                fill="#E4761B"
                stroke="#E4761B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M18.6139 21.7426L15.6347 20.2925L15.8719 22.2348L15.8456 23.0521L18.6139 21.7426Z"
                fill="#D7C1B3"
                stroke="#D7C1B3"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M9.38606 21.7426L12.1544 23.0521L12.1368 22.2348L12.3566 20.2925L9.38606 21.7426Z"
                fill="#D7C1B3"
                stroke="#D7C1B3"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M12.1984 17.0056L9.72002 16.2762L11.4689 15.4765L12.1984 17.0056Z"
                fill="#233447"
                stroke="#233447"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M15.7928 17.0056L16.5223 15.4765L18.28 16.2762L15.7928 17.0056Z"
                fill="#233447"
                stroke="#233447"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M9.38606 21.7426L9.80791 18.1745L7.05712 18.2536L9.38606 21.7426Z"
                fill="#CD6116"
                stroke="#CD6116"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M18.1921 18.1745L18.6139 21.7426L20.9429 18.2536L18.1921 18.1745Z"
                fill="#CD6116"
                stroke="#CD6116"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M20.2837 14.2461L15.3446 14.4658L15.8016 17.0057L16.5311 15.4765L18.2888 16.2762L20.2837 14.2461Z"
                fill="#CD6116"
                stroke="#CD6116"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M9.72002 16.2762L11.4777 15.4765L12.1984 17.0057L12.6642 14.4658L7.71626 14.2461L9.72002 16.2762Z"
                fill="#CD6116"
                stroke="#CD6116"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M7.71626 14.2461L9.79033 18.2888L9.72002 16.2762L7.71626 14.2461Z"
                fill="#E4751F"
                stroke="#E4751F"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M18.2888 16.2762L18.2009 18.2888L20.2837 14.2461L18.2888 16.2762Z"
                fill="#E4751F"
                stroke="#E4751F"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M12.6642 14.4658L12.1984 17.0057L12.7784 20.0025L12.9102 16.0565L12.6642 14.4658Z"
                fill="#E4751F"
                stroke="#E4751F"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M15.3446 14.4658L15.1073 16.0477L15.2128 20.0025L15.8016 17.0057L15.3446 14.4658Z"
                fill="#E4751F"
                stroke="#E4751F"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M15.8016 17.0056L15.2128 20.0025L15.6347 20.2925L18.2009 18.2888L18.2888 16.2762L15.8016 17.0056Z"
                fill="#F6851B"
                stroke="#F6851B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M9.72002 16.2762L9.79033 18.2888L12.3566 20.2925L12.7784 20.0025L12.1984 17.0056L9.72002 16.2762Z"
                fill="#F6851B"
                stroke="#F6851B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M15.8456 23.0521L15.8719 22.2348L15.6522 22.0414H12.339L12.1368 22.2348L12.1544 23.0521L9.38606 21.7426L10.3528 22.5336L12.3126 23.8958H15.6786L17.6472 22.5336L18.6139 21.7426L15.8456 23.0521Z"
                fill="#C0AD9E"
                stroke="#C0AD9E"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M15.6347 20.2925L15.2128 20.0025H12.7784L12.3566 20.2925L12.1368 22.2348L12.339 22.0414H15.6522L15.8719 22.2348L15.6347 20.2925Z"
                fill="#161616"
                stroke="#161616"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M24.4583 10.0364L25.2053 6.45072L24.0891 3.1199L15.6347 9.39485L18.8864 12.1456L23.4827 13.4903L24.5022 12.3038L24.0628 11.9874L24.7658 11.3459L24.221 10.924L24.924 10.3879L24.4583 10.0364Z"
                fill="#763D16"
                stroke="#763D16"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M2.79472 6.45072L3.54174 10.0364L3.06717 10.3879L3.77024 10.924L3.23415 11.3459L3.93722 11.9874L3.4978 12.3038L4.50847 13.4903L9.10483 12.1456L12.3566 9.39485L3.90207 3.1199L2.79472 6.45072Z"
                fill="#763D16"
                stroke="#763D16"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M23.4827 13.4903L18.8864 12.1456L20.2837 14.2461L18.2009 18.2888L20.9429 18.2536H25.0295L23.4827 13.4903Z"
                fill="#F6851B"
                stroke="#F6851B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M9.10484 12.1456L4.50848 13.4903L2.97929 18.2536H7.05713L9.79033 18.2888L7.71626 14.2461L9.10484 12.1456Z"
                fill="#F6851B"
                stroke="#F6851B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M15.3446 14.4658L15.6347 9.39485L16.9705 5.7828H11.0383L12.3566 9.39485L12.6642 14.4658L12.7696 16.0653L12.7784 20.0025H15.2128L15.2304 16.0653L15.3446 14.4658Z"
                fill="#F6851B"
                stroke="#F6851B"
                stroke-width="0.0878845"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path></svg
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              height="16"
              viewBox="0 0 152.407 108"
            >
              <g>
                <rect width="152.407" height="108" fill="transparent"></rect>
                <g>
                  <rect
                    x="60.4117"
                    y="25.6968"
                    width="31.5"
                    height="56.6064"
                    fill="#ff5f00"
                  ></rect>
                  <path
                    d="M382.20839,306a35.9375,35.9375,0,0,1,13.7499-28.3032,36,36,0,1,0,0,56.6064A35.938,35.938,0,0,1,382.20839,306Z"
                    transform="translate(-319.79649 -252)"
                    fill="#eb001b"
                  ></path>
                  <path
                    d="M454.20349,306a35.99867,35.99867,0,0,1-58.2452,28.3032,36.00518,36.00518,0,0,0,0-56.6064A35.99867,35.99867,0,0,1,454.20349,306Z"
                    transform="translate(-319.79649 -252)"
                    fill="#f79e1b"
                  ></path>
                  <path
                    d="M450.76889,328.3077v-1.1589h.4673v-.2361h-1.1901v.2361h.4675v1.1589Zm2.3105,0v-1.3973h-.3648l-.41959.9611-.41971-.9611h-.365v1.3973h.2576v-1.054l.3935.9087h.2671l.39351-.911v1.0563Z"
                    transform="translate(-319.79649 -252)"
                    fill="#f79e1b"
                  ></path>
                </g>
              </g></svg
            ><svg
              width="16"
              height="16"
              viewBox="0 0 28 28"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <rect width="28" height="28" rx="6" fill="#2C5FF6"></rect>
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M14.0002 23.8002C19.4126 23.8002 23.8002 19.4126 23.8002 14.0002C23.8002 8.5878 19.4126 4.2002 14.0002 4.2002C8.5878 4.2002 4.2002 8.5878 4.2002 14.0002C4.2002 19.4126 8.5878 23.8002 14.0002 23.8002ZM11.5502 10.8002C11.136 10.8002 10.8002 11.136 10.8002 11.5502V16.4502C10.8002 16.8644 11.136 17.2002 11.5502 17.2002H16.4502C16.8644 17.2002 17.2002 16.8644 17.2002 16.4502V11.5502C17.2002 11.136 16.8644 10.8002 16.4502 10.8002H11.5502Z"
                fill="white"
              ></path>
            </svg>
          </div>
        </button>
      </div>
    </div>
    <div class="conttit">
      <p class="yconp">
        <a target="_blank" href="https://bridge.degen.tips/"
          >The<strong class="fontsemibold"> Degen L3 chain</strong> is live now!
          <span
            >EVM compatible, low transaction fees, built for Degens!</span
          ></a
        >
      </p>
    </div>
    <div class="ycone">
      <div class="yconet">
        <div class="yoneb">
          <h1 class="yonetit">Turning content into currency.</h1>
          <div class="yonetxt">
            <p>
              Degen, an ERC-20 token launched in January 2024, has reshaped the
              Farcaster ecosystem by enabling Casters to reward others with
              DEGEN for posting quality content. Our points system recognizes
              unique posts and comments, effectively bridging the gap between
              online contributions and real-world value.
            </p>
          </div>
          <dl class="yonedl">
            <div class="text-right">
              <dt class="text-sky-400">Holders</dt>
              <dd class="yonedd">465k</dd>
            </div>
            <div class="text-right">
              <dt class="text-sky-400">Transactions</dt>
              <dd class="yonedd">6.00M</dd>
            </div>
            <div class="text-right">
              <dt class="text-sky-400">Fully Diluted Market Cap</dt>
              <dd class="yonedd">$281.93M</dd>
            </div>
            <div class="text-right">
              <dt class="text-sky-400">Price</dt>
              <dd class="yonedd">$0.008</dd>
            </div>
          </dl>
        </div>
      </div>
    </div>
    <div class="ycone">
      <div class="yconet">
        <div class="yoneb">
          <h1 class="ytwotit">Featured DApp</h1>
          <div class="ytwocon">
            <p data-slot="text" class="ytwoconp">
              <a
                href="https://www.alfafrens.com/"
                target="_blank"
                class="ytwocona"
                >AlfaFrens</a
              >
              offers private alpha chats for everyone. Subscribe and stake
              subscriptions to your favorite influencers with AlfaFrens using
              $DEGEN, powered by Superfluid.
            </p>
            <a target="_blank" href="https://www.alfafrens.com/"
              ><img
                alt="AlfaFrens"
                loading="lazy"
                class="ytwocimg"
                src="../assets/original.webp"
                style="color: transparent"
            /></a>
          </div>
        </div>
      </div>
    </div>
    <div class="footer">
      <div class="footconb">
        <div class="footcs">
          <div class="footcasb">
            <a
              target="_blank"
              class="footcasvg"
              href="https://twitter.com/degentokenbase"
              ><span class="sr-only">Twitter</span
              ><svg
                fill="currentColor"
                viewBox="0 0 24 24"
                class="fsvg"
                aria-hidden="true"
              >
                <path
                  d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"
                ></path></svg></a
            ><a
              target="_blank"
              class="footcasvg"
              href="https://www.supercast.xyz/channel/degentokenbase"
              ><span class="sr-only">Farcaster</span
              ><svg
                fill="currentColor"
                viewBox="0 0 1000 1000"
                class="fsvg"
                aria-hidden="true"
              >
                <path
                  d="M257.778 155.556H742.222V844.445H671.111V528.889H670.414C662.554 441.677 589.258 373.333 500 373.333C410.742 373.333 337.446 441.677 329.586 528.889H328.889V844.445H257.778V155.556Z"
                ></path>
                <path
                  d="M128.889 253.333L157.778 351.111H182.222V746.667C169.949 746.667 160 756.616 160 768.889V795.556H155.556C143.283 795.556 133.333 805.505 133.333 817.778V844.445H382.222V817.778C382.222 805.505 372.273 795.556 360 795.556H355.556V768.889C355.556 756.616 345.606 746.667 333.333 746.667H306.667V253.333H128.889Z"
                ></path>
                <path
                  d="M675.556 746.667C663.283 746.667 653.333 756.616 653.333 768.889V795.556H648.889C636.616 795.556 626.667 805.505 626.667 817.778V844.445H875.556V817.778C875.556 805.505 865.606 795.556 853.333 795.556H848.889V768.889C848.889 756.616 838.94 746.667 826.667 746.667V351.111H851.111L880 253.333H702.222V746.667H675.556Z"
                ></path></svg></a
            ><a
              target="_blank"
              class="footcasvg"
              href="https://t.me/degentokenbase"
              ><span class="sr-only">Telegram</span
              ><svg
                fill="currentColor"
                viewBox="0 0 1000 1000"
                version="1.1"
                xmlns="http://www.w3.org/2000/svg"
                class="fsvg"
                aria-hidden="true"
              >
                <title>Artboard</title>
                <desc>Created with Sketch.</desc>
                <defs>
                  <linearGradient
                    x1="50%"
                    y1="0%"
                    x2="50%"
                    y2="99.2583404%"
                    id="linearGradient-1"
                  >
                    <stop stop-color="currentColor" offset="0%"></stop>
                    <stop stop-color="currentColor" offset="100%"></stop>
                  </linearGradient>
                </defs>
                <g
                  id="Artboard"
                  stroke="none"
                  stroke-width="1"
                  fill="none"
                  fill-rule="evenodd"
                >
                  <circle
                    id="Oval"
                    fill="url(#linearGradient-1)"
                    cx="500"
                    cy="500"
                    r="500"
                  ></circle>
                  <path
                    d="M226.328419,494.722069 C372.088573,431.216685 469.284839,389.350049 517.917216,369.122161 C656.772535,311.36743 685.625481,301.334815 704.431427,301.003532 C708.567621,300.93067 717.815839,301.955743 723.806446,306.816707 C728.864797,310.92121 730.256552,316.46581 730.922551,320.357329 C731.588551,324.248848 732.417879,333.113828 731.758626,340.040666 C724.234007,419.102486 691.675104,610.964674 675.110982,699.515267 C668.10208,736.984342 654.301336,749.547532 640.940618,750.777006 C611.904684,753.448938 589.856115,731.588035 561.733393,713.153237 C517.726886,684.306416 492.866009,666.349181 450.150074,638.200013 C400.78442,605.66878 432.786119,587.789048 460.919462,558.568563 C468.282091,550.921423 596.21508,434.556479 598.691227,424.000355 C599.00091,422.680135 599.288312,417.758981 596.36474,415.160431 C593.441168,412.561881 589.126229,413.450484 586.012448,414.157198 C581.598758,415.158943 511.297793,461.625274 375.109553,553.556189 C355.154858,567.258623 337.080515,573.934908 320.886524,573.585046 C303.033948,573.199351 268.692754,563.490928 243.163606,555.192408 C211.851067,545.013936 186.964484,539.632504 189.131547,522.346309 C190.260287,513.342589 202.659244,504.134509 226.328419,494.722069 Z"
                    id="Path-3"
                    fill="#0f172a"
                  ></path>
                </g></svg></a
            ><a
              target="_blank"
              class="footcasvg"
              href="https://basescan.org/token/0x4ed4E862860beD51a9570b96d89aF5E1B0Efefed"
              ><span class="sr-only">Etherscan</span
              ><svg
                fill="currentColor"
                viewBox="0 0 122 122"
                class="fsvg"
                aria-hidden="true"
              >
                <path
                  d="M25.29 57.9139C25.2901 57.2347 25.4244 56.5623 25.6851 55.9352C25.9458 55.308 26.3278 54.7386 26.8092 54.2595C27.2907 53.7804 27.8619 53.4011 28.4903 53.1434C29.1187 52.8858 29.7918 52.7548 30.471 52.7579L39.061 52.7859C40.4305 52.7859 41.744 53.33 42.7124 54.2984C43.6809 55.2669 44.225 56.5803 44.225 57.9499V90.4299C45.192 90.1429 46.434 89.8369 47.793 89.5169C48.737 89.2952 49.5783 88.761 50.1805 88.0009C50.7826 87.2409 51.1102 86.2996 51.11 85.3299V45.0399C51.11 43.6702 51.654 42.3567 52.6224 41.3881C53.5908 40.4195 54.9043 39.8752 56.274 39.8749H64.881C66.2506 39.8752 67.5641 40.4195 68.5325 41.3881C69.5009 42.3567 70.045 43.6702 70.045 45.0399V82.4329C70.045 82.4329 72.2 81.5609 74.299 80.6749C75.0787 80.3452 75.7441 79.7931 76.2122 79.0877C76.6803 78.3822 76.9302 77.5545 76.931 76.7079V32.1299C76.931 30.7605 77.4749 29.4472 78.4431 28.4788C79.4113 27.5103 80.7245 26.9662 82.0939 26.9659H90.701C92.0706 26.9659 93.384 27.51 94.3525 28.4784C95.3209 29.4468 95.865 30.7603 95.865 32.1299V68.8389C103.327 63.4309 110.889 56.9269 116.89 49.1059C117.761 47.9707 118.337 46.6377 118.567 45.2257C118.797 43.8138 118.674 42.3668 118.209 41.0139C115.431 33.0217 111.016 25.6973 105.245 19.5096C99.474 13.3218 92.4749 8.40687 84.6955 5.07934C76.9161 1.75182 68.5277 0.0849617 60.0671 0.185439C51.6065 0.285917 43.2601 2.15152 35.562 5.66286C27.8638 9.17419 20.9834 14.2539 15.3611 20.577C9.73881 26.9001 5.49842 34.3272 2.91131 42.3832C0.324207 50.4391 -0.552649 58.9464 0.336851 67.3607C1.22635 75.775 3.86263 83.911 8.07696 91.2479C8.81111 92.5135 9.89118 93.5434 11.1903 94.2165C12.4894 94.8896 13.9536 95.178 15.411 95.0479C17.039 94.9049 19.066 94.7019 21.476 94.4189C22.5251 94.2998 23.4937 93.7989 24.1972 93.0116C24.9008 92.2244 25.2901 91.2058 25.291 90.1499L25.29 57.9139Z"
                  fill="currentColor"
                ></path>
                <path
                  d="M25.1021 110.009C34.1744 116.609 44.8959 120.571 56.0802 121.456C67.2646 122.34 78.4757 120.114 88.4731 115.022C98.4705 109.93 106.864 102.172 112.726 92.6059C118.587 83.0395 121.688 72.0381 121.685 60.8188C121.685 59.4188 121.62 58.0337 121.527 56.6567C99.308 89.7947 58.2831 105.287 25.104 110.004"
                  fill="currentColor"
                ></path></svg></a
            ><a
              target="_blank"
              class="footcasvg"
              href="https://www.coingecko.com/en/coins/degen-base"
              ><span class="sr-only">GeckoTerminal</span
              ><svg
                fill="currentColor"
                version="1.1"
                id="Layer_1"
                xmlns="http://www.w3.org/2000/svg"
                x="0px"
                y="0px"
                viewBox="0 0 1080 1080"
                class="fsvg"
                aria-hidden="true"
              >
                <g id="XMLID_200_">
                  <g id="XMLID_202_">
                    <g>
                      <path
                        d="M536.6-1C238.3,0.4-2.3,243.2-1,541.4c1.4,298.2,244.2,538.9,542.4,537.6c298.2-1.4,538.9-244.2,537.6-542.4     C1077.6,238.3,834.8-2.3,536.6-1z M468.2,512.5c-53.3,0-96.6-43.2-96.6-96.5c0-53.3,43.2-96.5,96.6-96.5     c53.3,0,96.5,43.2,96.5,96.5C564.7,469.3,521.5,512.5,468.2,512.5z M545.2,616.9l0.5-0.6l0.5-0.6c27.6,17.8,59,24,90.4,25     c31.5,0.8,63.5-1.5,95.1-7.9c31.5-6.5,62.5-16.2,92.4-28.6c16.8-6.9,33.5-14.5,49.4-23.4c0.1-0.1,0.2-0.1,0.3-0.2     c9.9-6,19.6-12.2,29.1-18.7c2.1-1.5,4.1-3,6-4.6l0.2,0.3l0.8,1c-24.3,22.1-53.2,38.5-82.6,53c-29.7,14-60.7,25.5-92.7,33.8     c-31.9,8.2-65.2,14.5-98.9,11.4C602.5,653.7,567.5,642.1,545.2,616.9z M793,512.5c0-11.6,9.3-20.9,20.8-21     c11.6,0,20.9,9.3,21,20.8c0,11.5-9.3,21-20.8,21C802.5,533.4,793,524.1,793,512.5z M627.6,1030.5     C606.7,884.3,734.3,741.2,806.3,668c16.3-16.6,41.6-39.5,65.1-63.8c93.4-87.3,112-191.7-79.2-243.9     c-36.2-10.5-73.8-25.4-111.8-40.4c-1.2-3.5-2.6-6.8-4.1-9.9c-4.4-7.5-12-16.2-23.6-26c-24.9-21.6-71.5-21-111.8-11.5     c-44.6-10.5-88.5-14.2-130.8-4.1c-184.9,50.9-214.6,141.1-221.8,249.8c-9.8,117.4-15.5,204.9-60,304.9     C72.8,743,40.1,646,39.7,541.2C38.5,265.5,261,40.9,536.8,39.7c275.8-1.2,500.3,221.3,501.6,497.1     C1039.4,783.1,862,988.6,627.6,1030.5z"
                      ></path>
                    </g>
                  </g>
                  <path
                    id="XMLID_201_"
                    d="M536.1,416.9c0,37.5-30.4,67.9-67.9,67.9c-37.5,0-67.9-30.4-67.9-67.9s30.4-67.9,67.9-67.9   C505.7,349,536.1,379.4,536.1,416.9z"
                  ></path>
                </g></svg
            ></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from "vue";

let render = () => {
  ms_init();
};
</script>

<style scoped>
.ymain {
  width: 100%;
}
.yvideo {
  opacity: 0.15;
  object-fit: cover;
  width: 100%;
  position: fixed;
  display: block;
  vertical-align: middle;
  z-index: -1;
}
.header {
  width: 100%;
  background: rgb(30 41 59);
  padding: 1.5rem 2.5rem;
  box-sizing: border-box;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.headl {
  flex: 1 1 0%;
  display: flex;
}
.headllink {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0.375rem;
  margin: -0.375rem;
  box-sizing: border-box;
}
.headlsvg {
  width: auto;
  height: 2rem;
  color: rgb(139 92 246);
}
.headlsvg:hover {
  color: rgb(124 58 237);
}
.headc {
  font-family: "protoMono";
  display: flex;
  column-gap: 3rem;
  line-height: 1.5rem;
  font-weight: 600;
}
.headcbut {
  font-family: "protoMono";
  font-weight: 600;
  font-size: 1rem;
  line-height: 1.5rem;
  outline: 2px solid transparent;
  outline-offset: 2px;
  color: rgb(224 242 254);
  column-gap: 0.25rem;
  display: flex;
  align-items: center;
  background: transparent;
}
.headcsvg {
  width: 1.25rem;
  height: 1.25rem;
}
.headca {
  font-family: "protoMono";
  font-weight: 600;
  font-size: 1rem;
  line-height: 1.5rem;
  color: rgb(224 242 254);
}
.headca:hover {
  color: rgb(99 102 241);
}
.headr {
  display: flex;
  justify-content: flex-end;
  flex: 1 1 0%;
  margin-left: 1.25rem;
  flex-grow: 1;
  flex-basis: 0px;
}
.headrbut {
  font-family: "protoMono";
  font-weight: 600;
  display: inline-flex;
  cursor: pointer;
  justify-content: center;
  align-items: center;
  column-gap: 0.5rem;
  color: rgb(15 23 42);
  font-size: 0.875rem;
  line-height: 1.5rem;
  background: rgba(124, 58, 237, 0.9);
  padding: calc(0.375rem - 1px) calc(0.75rem - 1px);
  box-sizing: border-box;
}
.headrbut:hover {
  background: rgb(151, 109, 247);
}
.headrsvgs {
  display: flex;
  justify-content: center;
  gap: 2px;
  align-items: center;
}
.conttit {
  display: flex;
  align-items: center;
  column-gap: 1.5rem;
  background-color: rgba(2, 6, 23, 0.55);
  padding: 0.625rem 0.875rem;
  box-sizing: border-box;
}
.yconp {
  flex: 1 1 0%;
  display: flex;
  justify-content: center;
  line-height: 1.5rem;
  font-size: 0.875rem;
}
.yconp > a {
  color: rgb(224 242 254);
  font-family: "protoMono";
}
.fontsemibold {
  font-weight: 600;
}
.ycone {
  width: 100%;
  padding: 3rem 0;
  box-sizing: border-box;
}
.yconet {
  width: 80rem;
  padding: 0 2rem;
  box-sizing: border-box;
  margin: 0 auto;
}
.yoneb {
  width: 56rem;
  padding: 4rem 3rem;
  background-color: rgba(2, 6, 23, 0.55);
  margin: 0 auto;
  box-sizing: border-box;
}
.yonetit {
  font-family: "protoMonobold";
  font-weight: 700;
  font-size: 4.5rem;
  line-height: 1;
  color: rgb(56 189 248);
}
.yonetxt {
  font-family: "protoMono";
  font-size: 1.5rem;
  line-height: 2rem;
  margin-top: 1.5rem;
  color: rgb(224 242 254);
}
.yonedl {
  margin-top: 4rem;
  display: grid;
  column-gap: 4rem;
  row-gap: 2.5rem;
  justify-content: space-between;
  grid-template-columns: none;
  grid-auto-flow: column;
  grid-auto-columns: auto;
}
.text-right {
  text-align: right;
}
.text-sky-400 {
  font-family: "protoMono";
  font-size: 1rem;
  line-height: 1.5rem;
  color: rgb(56 189 248);
}
.yonedd {
  font-family: "protoMono";
  font-weight: 600;
  margin-top: 0.125rem;
  font-size: 1.5rem;
  line-height: 2rem;
  color: rgb(224 242 254);
}
.ytwotit {
  font-family: "protoMonobold";
  font-weight: 700;
  font-size: 3rem;
  line-height: 1;
  color: rgb(56 189 248);
}
.ytwocon {
  margin-top: 1.5rem;
}
.ytwoconp {
  font-family: "protoMono";
  font-weight: 400;
  font-size: 1.125rem;
  line-height: 1.75rem;
  color: rgb(224 242 254);
}
.ytwocona {
  font-family: "protoMono";
  font-weight: 400;
  font-size: 1.125rem;
  line-height: 1.75rem;
  color: rgb(167 139 250);
  text-decoration-line: underline;
  text-decoration-color: #8b5cf6;
}
.ytwocimg {
  object-fit: cover;
  color: transparent;
  border-radius: 0.75rem;
  margin-top: 2rem;
  width: 50rem;
  height: 28.125rem;
}
.footer {
  width: 100%;
  padding: 1rem 0;
  box-sizing: border-box;
}
.footconb {
  width: 80rem;
  padding: 0 2rem;
  margin: 0 auto;
  box-sizing: border-box;
}
.footcs {
  width: 100%;
  padding: 1rem 0;
  box-sizing: border-box;
  border-top: 1px solid rgb(51 65 85);
}
.footcasb {
  text-align: left;
  width: 32rem;
  display: flex;
  gap: 1.5rem;
}
.footcasvg {
  color: rgb(100 116 139);
}
.footcasvg:hover {
  color: rgb(51 65 85);
}
.sr-only {
  display: none;
}
.fsvg {
  width: 1.5rem;
  height: 1.5rem;
}
@media (max-width: 1250px) {
  .header {
    padding: 1.5rem 1rem;
  }
  .headc {
    display: none;
  }
  .headrsvgs {
    display: none;
  }
  .conttit {
    padding: 0.625rem 1.5rem;
  }
  .yconp span {
    display: none;
  }
  .yconet {
    width: 100%;
    padding: 0 1rem;
  }
  .yoneb {
    width: 100%;
    padding: 2rem 1rem;
  }
  .yonetit {
    font-size: 3rem;
  }
  .yonetxt {
    font-size: 1.25rem;
    line-height: 1.75rem;
  }
  .yonedl {
    margin-top: 2.5rem;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    column-gap: 2.5rem;
    row-gap: 1.5rem;
    grid-auto-flow: initial;
  }
  .ytwotit {
    font-size: 2.25rem;
    line-height: 2.5rem;
  }
  .ytwocimg {
    width: 100%;
    height: auto;
  }
  .footconb {
    width: 100%;
    padding: 0 1rem;
  }
  .footcs {
    padding: 1.5rem 0;
  }
  .yvideo {
    max-width: 100%;
    min-width: 100%;
    min-height: 100%;
    height: auto;
  }
}
</style>
