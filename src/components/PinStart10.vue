<template>
  <div :class="{ 'active-pin': activePin === 'pin10' }" class="pin-start pin10">
    <app-pin-popup
      :title="`Начать`"
      :dscr="`Нажмите на кнопку «Старт», чтобы начать игру`"
      v-if="activePin === 'pin10'"
    ></app-pin-popup>
    <svg
      width="223"
      height="203"
      viewBox="0 0 223 203"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <ellipse
        opacity="0.6"
        cx="107"
        cy="163.5"
        rx="96"
        ry="39.5"
        fill="url(#paint0_radial)"
      />
      <path
        d="M147.159 136.812C169.614 149.894 169.614 171.106 147.158 184.188C124.703 197.271 88.2963 197.271 65.8413 184.188C43.3862 171.106 43.3862 149.895 65.8416 136.812C88.2967 123.729 124.704 123.729 147.159 136.812Z"
        stroke="url(#paint1_linear)"
        stroke-width="5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round"
      />
      <path
        d="M147.159 136.812C169.614 149.894 169.614 171.106 147.158 184.188C124.703 197.271 88.2963 197.271 65.8413 184.188C43.3862 171.106 43.3862 149.895 65.8416 136.812C88.2967 123.729 124.704 123.729 147.159 136.812Z"
        stroke="url(#paint2_linear)"
        stroke-width="5"
        stroke-miterlimit="10"
        stroke-linecap="round"
        stroke-linejoin="round"
      />
      <g opacity="0.5">
        <path
          d="M137.966 140.469C155.345 150.427 155.345 166.573 137.966 176.531C120.588 186.49 92.412 186.49 75.0337 176.531C57.6554 166.573 57.6554 150.427 75.034 140.469C92.4122 130.51 120.588 130.51 137.966 140.469Z"
          stroke="url(#paint3_linear)"
          stroke-width="2"
          stroke-miterlimit="10"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
        <path
          d="M137.966 140.469C155.345 150.427 155.345 166.573 137.966 176.531C120.588 186.49 92.412 186.49 75.0337 176.531C57.6554 166.573 57.6554 150.427 75.034 140.469C92.4122 130.51 120.588 130.51 137.966 140.469Z"
          stroke="url(#paint4_linear)"
          stroke-width="2"
          stroke-miterlimit="10"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </g>
      <ellipse
        cx="106.481"
        cy="157.72"
        rx="31.9829"
        ry="18.9561"
        fill="#3F45A6"
      />
      <ellipse
        cx="106.481"
        cy="157.72"
        rx="31.9829"
        ry="18.9561"
        fill="#626AFF"
      />
      <ellipse
        cx="106.481"
        cy="157.72"
        rx="35.121"
        ry="21.4232"
        fill="#626AFF"
        fill-opacity="0.5"
      />
      <ellipse
        cx="106.481"
        cy="157.731"
        rx="38.4807"
        ry="24.3757"
        fill="#626AFF"
        fill-opacity="0.3"
      />
      <ellipse
        cx="106.481"
        cy="157.665"
        rx="29.182"
        ry="16.551"
        fill="#6419AE"
      />
      <ellipse
        cx="106.481"
        cy="157.422"
        rx="25.9715"
        ry="13.7402"
        fill="#9E8EFF"
      />
      <path
        opacity="0.8"
        d="M145 16H68L76.9448 153.07C78.5 164.5 88.4479 173 106.501 173C124.555 173 135 165.5 136.055 153.07L145 16Z"
        fill="url(#paint5_linear)"
        fill-opacity="0.8"
      />
      <path
        d="M132.254 138.648C132.669 138.648 133.005 138.312 133.005 137.897C133.005 137.483 132.669 137.146 132.254 137.146C131.84 137.146 131.503 137.483 131.503 137.897C131.503 138.312 131.84 138.648 132.254 138.648Z"
        fill="#48D8F5"
      />
      <path
        d="M129.359 114.872C129.568 114.872 129.737 114.703 129.737 114.494C129.737 114.285 129.568 114.115 129.359 114.115C129.15 114.115 128.98 114.285 128.98 114.494C128.98 114.703 129.15 114.872 129.359 114.872Z"
        fill="#48D8F5"
      />
      <path
        d="M135.067 98.3133C135.067 98.4178 134.983 98.5008 134.879 98.5008C134.778 98.5008 134.693 98.4178 134.693 98.3133C134.693 98.2108 134.778 98.127 134.879 98.127C134.983 98.127 135.067 98.2108 135.067 98.3133Z"
        fill="#48D8F5"
      />
      <path
        d="M128.187 130.286C128.29 130.286 128.374 130.203 128.374 130.099C128.374 129.996 128.29 129.912 128.187 129.912C128.084 129.912 128 129.996 128 130.099C128 130.203 128.084 130.286 128.187 130.286Z"
        fill="#48D8F5"
      />
      <path
        d="M135.435 109.259C135.538 109.259 135.622 109.175 135.622 109.072C135.622 108.969 135.538 108.885 135.435 108.885C135.331 108.885 135.247 108.969 135.247 109.072C135.247 109.175 135.331 109.259 135.435 109.259Z"
        fill="#48D8F5"
      />
      <path
        d="M133.006 122.975C133.215 122.975 133.384 122.805 133.384 122.597C133.384 122.388 133.215 122.219 133.006 122.219C132.798 122.219 132.628 122.388 132.628 122.597C132.628 122.805 132.798 122.975 133.006 122.975Z"
        fill="#48D8F5"
      />
      <path
        d="M82.1817 112.453C82.2156 112.867 81.9095 113.229 81.496 113.263C81.0841 113.298 80.7198 112.989 80.6859 112.577C80.6508 112.164 80.9606 111.802 81.3716 111.767C81.7856 111.733 82.1486 112.04 82.1817 112.453Z"
        fill="#48D8F5"
      />
      <path
        d="M89.1885 123.184C89.2244 123.597 88.9158 123.96 88.5024 123.993C88.0897 124.028 87.7278 123.719 87.6936 123.307C87.6584 122.895 87.9662 122.532 88.3793 122.498C88.7911 122.463 89.1554 122.77 89.1885 123.184Z"
        fill="#48D8F5"
      />
      <path
        d="M84.86 101.486C84.8778 101.694 84.7208 101.878 84.513 101.895C84.3052 101.912 84.1243 101.757 84.1061 101.549C84.088 101.34 84.2416 101.157 84.4515 101.141C84.6592 101.123 84.8439 101.278 84.86 101.486Z"
        fill="#48D8F5"
      />
      <path
        d="M77.3729 103.907C77.3815 104.01 77.3051 104.101 77.2039 104.11C77.0994 104.118 77.0085 104.041 77.0007 103.938C76.992 103.835 77.0684 103.745 77.1717 103.736C77.2741 103.728 77.365 103.804 77.3729 103.907Z"
        fill="#48D8F5"
      />
      <path
        d="M86.9635 129.303C86.9713 129.405 86.8945 129.497 86.7925 129.505C86.6888 129.513 86.5991 129.437 86.5905 129.334C86.581 129.231 86.6603 129.141 86.7598 129.133C86.8647 129.122 86.9531 129.199 86.9635 129.303Z"
        fill="#48D8F5"
      />
      <path
        d="M81.9604 123.401C81.9786 123.609 81.8212 123.792 81.6143 123.809C81.4061 123.825 81.2239 123.671 81.207 123.463C81.19 123.255 81.3437 123.071 81.5523 123.054C81.7592 123.038 81.9427 123.193 81.9604 123.401Z"
        fill="#48D8F5"
      />
      <path
        d="M85.1956 136.013C85.2142 136.221 85.0572 136.404 84.8507 136.421C84.6417 136.438 84.4599 136.284 84.4417 136.076C84.4264 135.868 84.5797 135.685 84.7887 135.667C84.9969 135.65 85.1791 135.805 85.1956 136.013Z"
        fill="#48D8F5"
      />
      <path
        d="M81.072 141.704C81.0881 141.911 80.9336 142.094 80.7267 142.112C80.516 142.128 80.3343 141.975 80.3161 141.765C80.2996 141.558 80.4553 141.375 80.6635 141.358C80.8729 141.341 81.0547 141.495 81.072 141.704Z"
        fill="#48D8F5"
      />
      <g opacity="0.3">
        <path
          d="M146 14H69L77.9448 151.07C82.4604 165.101 89.4479 171 107.501 171C125.555 171 134.399 165.456 137.055 151.07L146 14Z"
          fill="url(#paint6_linear)"
        />
        <path
          d="M146 14H69L77.9448 151.07C82.4604 165.101 89.4479 171 107.501 171C125.555 171 134.399 165.456 137.055 151.07L146 14Z"
          fill="url(#paint7_linear)"
          fill-opacity="0.5"
        />
      </g>
      <path
        opacity="0.3"
        d="M146 14H69L77.9448 151.07C82.4604 165.101 89.4479 171 107.501 171C125.555 171 134.399 165.456 137.055 151.07L146 14Z"
        fill="url(#paint8_linear)"
        fill-opacity="0.3"
      />
      <g style="mix-blend-mode: color-dodge">
        <path
          d="M107 170C119.703 170 130 164.404 130 157.5C130 150.596 119.703 145 107 145C94.2975 145 84 150.596 84 157.5C84 164.404 94.2975 170 107 170Z"
          fill="url(#paint9_radial)"
        />
      </g>
      <path
        d="M99.4716 81.807L113.152 116.43L137.668 85.4607L123.877 50.5594L99.4716 81.807Z"
        fill="url(#paint10_linear)"
      />
      <path
        d="M99.3835 81.9529L113.064 116.576L137.579 85.6065L123.883 50.5132L99.3835 81.9529Z"
        fill="url(#paint11_linear)"
      />
      <path
        d="M99.3828 81.7104L113.206 116.888L73.9584 111.053L60.1309 75.5868L99.3828 81.7104Z"
        fill="url(#paint12_linear)"
      />
      <path
        d="M60.1543 75.6765L99.512 81.7907L123.877 50.559L84.4888 44.5706L60.1543 75.6765Z"
        fill="url(#paint13_linear)"
      />
      <g style="mix-blend-mode: color-dodge">
        <path
          d="M60.1543 75.6765L99.512 81.7907L123.877 50.559L84.4888 44.5706L60.1543 75.6765Z"
          fill="url(#paint14_linear)"
        />
        <path
          d="M60.1543 75.6765L99.512 81.7907L123.877 50.559L84.4888 44.5706L60.1543 75.6765Z"
          stroke="#00FFFF"
          stroke-width="0.39766"
          stroke-linejoin="round"
        />
      </g>
      <g filter="url(#filter0_d)">
        <path
          d="M109.779 68.7528L123.341 103.122L127.833 97.4359L114.247 62.9644L109.779 68.7528Z"
          fill="url(#paint15_linear)"
        />
      </g>
      <g filter="url(#filter1_d)">
        <path
          d="M70.7221 62.6714L109.82 68.7374L114.247 62.9649L75.14 57.0752L70.7221 62.6714Z"
          fill="url(#paint16_linear)"
        />
      </g>
      <g filter="url(#filter2_d)">
        <path
          d="M83.1257 79.3867L96.8455 114.109L89.9495 113.235L76.1199 78.2344L83.1257 79.3867Z"
          fill="url(#paint17_linear)"
        />
      </g>
      <g filter="url(#filter3_d)">
        <path
          d="M107.482 48.3974L83.0873 79.4022L76.1217 78.234L100.512 47.3375L107.482 48.3974Z"
          fill="url(#paint18_linear)"
        />
      </g>
      <path
        fill-rule="evenodd"
        clip-rule="evenodd"
        d="M99.4461 81.8721L99.3826 81.7104L60.1307 75.5868L73.9582 111.053L113.206 116.888L113.076 116.56L137.579 85.6063L123.882 50.513L99.4461 81.8721Z"
        fill="url(#paint19_radial)"
        style="mix-blend-mode: hard-light"
      />
      <path
        d="M79.9926 60.6227C79.0235 59.9852 78.7313 59.0583 78.7063 58.6745C78.8342 57.9316 79.4433 57.635 79.7319 57.5796L82.2757 57.5132L86.7976 62.2741C86.894 62.3584 87.1511 62.7517 87.4082 63.6506C84.8215 63.6817 81.2039 61.4197 79.9926 60.6227Z"
        fill="url(#paint20_linear)"
      />
      <path
        d="M102.71 52.751C102.845 51.7765 102.215 51.1011 101.883 50.8852C101.123 50.3509 100.306 50.7679 99.9922 51.0431C99.0203 52.9447 97.1325 57.1806 97.3557 58.9114C101.333 59.8974 102.543 53.9691 102.71 52.751Z"
        fill="url(#paint21_linear)"
      />
      <path
        d="M87.7421 54.2448C88.9243 55.0928 90.114 56.0518 90.5611 56.4253C89.559 58.1769 87.3824 61.8437 86.6925 62.4983C85.7192 62.8212 82.1455 59.3688 80.9052 58.4758C79.6649 57.5828 78.8834 58.3379 78.7592 58.8559C78.2846 58.0317 78.9399 57.1147 80.1668 55.3995C81.3938 53.6843 82.3498 52.7701 83.5102 52.2553C84.6706 51.7405 86.2643 53.1848 87.7421 54.2448Z"
        fill="url(#paint22_linear)"
      />
      <path
        d="M93.1739 50.2828C92.7031 51.3086 91.677 54.9498 91.3702 56.284C92.8543 56.724 96.0054 57.7461 96.7369 58.3147C96.8219 59.6113 97.5931 59.0786 97.9806 57.9264C98.5864 55.4247 99.4101 53.3745 100.077 52.0947C100.945 50.4298 101.625 50.9181 102.36 51.4089C101.631 49.5811 98.3914 48.7852 96.4784 48.4629C94.5654 48.1406 93.6447 49.2571 93.1739 50.2828Z"
        fill="url(#paint23_linear)"
      />
      <path
        d="M93.9174 66.7682C93.0639 66.194 93.1238 65.2918 93.1562 64.6692C97.2401 62.9067 100.126 64.966 101.063 66.226C101.332 66.8328 101.503 68.1385 100.033 68.5075C98.1953 68.9687 95.0017 67.4975 93.9174 66.7682Z"
        fill="url(#paint24_linear)"
      />
      <path
        d="M93.5915 65.2509C93.0625 65.4856 92.7574 64.5522 92.8091 64.4543C92.645 64.3093 92.1866 63.6984 92.0073 62.7541C91.7832 61.5736 93.4707 59.0551 94.9803 57.9769C96.4899 56.8988 96.6307 57.9528 96.8879 58.6556C100.897 57.7486 101.978 58.4671 103.562 59.3983C105.146 60.3294 105.001 61.7826 104.748 62.9298C104.494 64.077 103.998 64.9233 102.832 66.7751C101.665 68.6268 100.396 68.8357 99.805 68.853C96.7701 68.9358 94.5392 67.4396 93.7765 66.6615C94.8897 67.3295 97.4476 68.5971 98.9864 68.4809C100.91 68.3356 100.701 67.3119 99.087 65.577C97.4732 63.8421 94.5699 64.8169 93.5915 65.2509Z"
        fill="url(#paint25_linear)"
      />
      <path
        d="M94.0337 66.2402C94.1901 66.0156 93.7347 65.2285 93.4908 65.208C92.1615 65.0965 89.7433 66.1828 87.5738 67.6762C85.4043 69.1696 86.3114 71.2452 87.2751 71.975C88.2388 72.7049 89.4602 71.5912 90.7893 70.3208C92.1183 69.0505 93.8383 66.5209 94.0337 66.2402Z"
        fill="url(#paint26_linear)"
      />
      <path
        d="M84.3546 63.1812C85.3557 62.7371 86.2733 62.4934 86.607 62.4271L92.6196 64.1031C92.6743 64.2059 93.0273 64.5479 93.5201 65.266C91.182 65.7041 89.2097 66.6369 87.7279 67.8389C86.246 69.0409 86.6544 70.5753 86.8386 70.9292C87.0229 71.2832 87.318 72.1326 88.6349 71.8479C89.6885 71.6202 92.6788 68.0117 94.0423 66.2359C93.6408 66.886 92.4802 68.6444 91.0495 70.4773C89.2611 72.7683 87.9393 72.6739 87.262 72.6203C86.5847 72.5668 82.5472 70.954 81.6755 70.5238C80.8039 70.0935 79.8726 68.301 80.6701 66.2317C81.4677 64.1623 83.1032 63.7363 84.3546 63.1812Z"
        fill="url(#paint27_linear)"
      />
      <path
        d="M95.5069 56.9546C97.5863 57.6116 96.9969 58.4721 96.7793 58.8409C96.379 56.6494 93.9304 59.7235 92.9561 61.5172C92.2707 62.7791 92.4783 63.9803 92.82 64.4641C91.1507 63.9339 87.5704 62.7954 86.6041 62.4834C85.3727 59.7075 88.8148 56.6012 90.5236 56.0337C91.6356 55.6645 93.9812 56.4726 95.5069 56.9546Z"
        fill="url(#paint28_linear)"
      />
      <path
        d="M108.27 79.8421C108.962 80.0256 109.672 79.6135 109.855 78.9217C110.038 78.23 109.626 77.5205 108.935 77.337C108.243 77.1536 107.533 77.5657 107.35 78.2574C107.166 78.9492 107.579 79.6587 108.27 79.8421Z"
        fill="#FF00F2"
        fill-opacity="0.3"
      />
      <path
        d="M113.956 38.9051C114.304 38.9975 114.662 38.7899 114.754 38.4414C114.847 38.0928 114.639 37.7354 114.29 37.6429C113.942 37.5505 113.584 37.7581 113.492 38.1067C113.4 38.4552 113.607 38.8127 113.956 38.9051Z"
        fill="#FF00F2"
        fill-opacity="0.3"
      />
      <path
        d="M130.801 13.8122C130.754 13.9865 130.577 14.0877 130.405 14.042C130.235 13.9971 130.13 13.821 130.176 13.6467C130.222 13.4758 130.401 13.3736 130.57 13.4185C130.742 13.4642 130.846 13.6413 130.801 13.8122Z"
        fill="#FF00F2"
        fill-opacity="0.3"
      />
      <path
        d="M105.184 64.0966C105.356 64.1423 105.533 64.0396 105.579 63.8673C105.625 63.6949 105.522 63.5181 105.349 63.4724C105.177 63.4267 105 63.5294 104.955 63.7017C104.909 63.8741 105.012 64.0509 105.184 64.0966Z"
        fill="#FF00F2"
        fill-opacity="0.3"
      />
      <path
        d="M126.574 32.2314C126.746 32.2771 126.923 32.1744 126.969 32.002C127.014 31.8297 126.912 31.6529 126.739 31.6072C126.567 31.5615 126.39 31.6641 126.345 31.8365C126.299 32.0089 126.402 32.1857 126.574 32.2314Z"
        fill="#FF00F2"
        fill-opacity="0.3"
      />
      <path
        d="M116.455 54.0344C116.803 54.1268 117.16 53.9194 117.252 53.5712C117.344 53.223 117.137 52.8659 116.789 52.7736C116.441 52.6813 116.084 52.8887 115.991 53.2368C115.899 53.585 116.106 53.9421 116.455 54.0344Z"
        fill="#FF00F2"
        fill-opacity="0.3"
      />
      <g style="mix-blend-mode: lighten" filter="url(#filter4_f)">
        <path
          d="M50.9505 40.5248C50.4434 41.0298 50.4419 41.8503 50.947 42.3573C51.452 42.8643 52.2725 42.8659 52.7795 42.3608C53.2866 41.8557 53.2881 41.0353 52.783 40.5283C52.2779 40.0212 51.4575 40.0197 50.9505 40.5248Z"
          fill="#FF00F2"
          fill-opacity="0.3"
        />
        <path
          d="M83.4455 66.063C83.19 66.3175 83.1892 66.7309 83.4437 66.9864C83.6982 67.2418 84.1116 67.2426 84.367 66.9881C84.6225 66.7336 84.6233 66.3203 84.3688 66.0648C84.1143 65.8093 83.7009 65.8085 83.4455 66.063Z"
          fill="#FF00F2"
          fill-opacity="0.3"
        />
        <path
          d="M96.6326 93.2573C96.5053 93.1296 96.5072 92.9254 96.6335 92.7997C96.7577 92.6759 96.9628 92.6738 97.0901 92.8016C97.2149 92.9268 97.213 93.1329 97.0887 93.2567C96.9625 93.3824 96.7574 93.3826 96.6326 93.2573Z"
          fill="#FF00F2"
          fill-opacity="0.3"
        />
        <path
          d="M66.1061 45.7928C65.9798 45.9187 65.9794 46.1231 66.1053 46.2495C66.2311 46.3758 66.4356 46.3762 66.5619 46.2503C66.6882 46.1245 66.6886 45.92 66.5628 45.7937C66.4369 45.6674 66.2325 45.667 66.1061 45.7928Z"
          fill="#FF00F2"
          fill-opacity="0.3"
        />
        <path
          d="M82.8524 80.326C82.726 80.4519 82.7256 80.6563 82.8515 80.7827C82.9773 80.909 83.1818 80.9094 83.3081 80.7835C83.4344 80.6577 83.4348 80.4532 83.309 80.3269C83.1831 80.2006 82.9787 80.2002 82.8524 80.326Z"
          fill="#FF00F2"
          fill-opacity="0.3"
        />
        <path
          d="M69.1188 60.5987C68.8637 60.8529 68.8629 61.2658 69.1171 61.521C69.3713 61.7762 69.7842 61.777 70.0394 61.5228C70.2946 61.2686 70.2954 60.8556 70.0412 60.6005C69.787 60.3453 69.374 60.3445 69.1188 60.5987Z"
          fill="#FF00F2"
          fill-opacity="0.3"
        />
      </g>
      <g style="mix-blend-mode: screen" filter="url(#filter5_f)">
        <path
          d="M92.6923 38.3081C92.949 38.9764 92.618 39.7254 91.9495 39.9814C91.2846 40.2393 90.5316 39.9051 90.2753 39.2382C90.017 38.5718 90.3543 37.8217 91.0181 37.5648C91.6871 37.308 92.4372 37.6401 92.6923 38.3081Z"
          fill="white"
        />
        <path
          d="M109.499 52.6778C109.758 53.3437 109.424 54.0954 108.755 54.35C108.088 54.6083 107.34 54.2728 107.083 53.6061C106.825 52.9412 107.158 52.1906 107.826 51.9342C108.491 51.6769 109.243 52.0091 109.499 52.6778Z"
          fill="white"
        />
        <path
          d="M91.8053 18.8469C91.9355 19.1824 91.7647 19.5629 91.4288 19.6918C91.0932 19.8213 90.7182 19.6518 90.5874 19.3166C90.4561 18.98 90.6218 18.6024 90.9614 18.4739C91.2965 18.3424 91.6778 18.5107 91.8053 18.8469Z"
          fill="white"
        />
        <path
          d="M80.5814 26.487C80.6459 26.6538 80.5634 26.8414 80.4003 26.9055C80.2308 26.9685 80.0432 26.8861 79.9802 26.7189C79.9161 26.5534 79.9986 26.3659 80.1654 26.3014C80.3312 26.2387 80.5188 26.3212 80.5814 26.487Z"
          fill="white"
        />
        <path
          d="M108.783 63.8908C108.845 64.056 108.762 64.2444 108.597 64.3069C108.43 64.3716 108.244 64.2885 108.18 64.1217C108.114 63.9567 108.202 63.7684 108.363 63.7071C108.532 63.6391 108.715 63.7228 108.783 63.8908Z"
          fill="white"
        />
        <path
          d="M97.6345 56.5441C97.7652 56.8787 97.5938 57.2594 97.2591 57.3871C96.9221 57.5148 96.5459 57.3487 96.4167 57.0115C96.2879 56.6756 96.4532 56.2967 96.7902 56.1668C97.1251 56.0397 97.5039 56.2073 97.6345 56.5441Z"
          fill="white"
        />
        <path
          d="M109.11 75.8591C109.242 76.1956 109.071 76.5747 108.737 76.7023C108.399 76.8324 108.023 76.6647 107.892 76.3295C107.766 75.9928 107.931 75.6161 108.269 75.4846C108.605 75.3556 108.982 75.5238 109.11 75.8591Z"
          fill="white"
        />
        <path
          d="M105.041 87.2842C105.168 87.6197 105.001 87.9977 104.667 88.1282C104.326 88.2563 103.951 88.0914 103.819 87.7527C103.691 87.4167 103.86 87.0388 104.196 86.9091C104.535 86.7801 104.911 86.9464 105.041 87.2842Z"
          fill="white"
        />
      </g>
      <g style="mix-blend-mode: color-dodge">
        <path
          d="M133 156C133 164.285 121.583 171 107.499 171C93.4169 171 82 164.285 82 156C82 147.716 93.4169 141 107.499 141C121.583 141 133 147.716 133 156Z"
          fill="url(#paint29_radial)"
        />
      </g>
      <path
        d="M117.416 153.574C122.909 156.744 122.909 161.885 117.416 165.055C111.925 168.226 103.02 168.226 97.5305 165.055C92.0395 161.884 92.0395 156.744 97.5305 153.574C103.02 150.404 111.925 150.404 117.416 153.574Z"
        fill="white"
      />
      <path
        d="M120.66 143.954C121.075 143.954 121.411 143.618 121.411 143.203C121.411 142.788 121.075 142.452 120.66 142.452C120.245 142.452 119.909 142.788 119.909 143.203C119.909 143.618 120.245 143.954 120.66 143.954Z"
        fill="#48D8F5"
      />
      <path
        d="M117.764 120.178C117.973 120.178 118.142 120.008 118.142 119.799C118.142 119.59 117.973 119.421 117.764 119.421C117.555 119.421 117.386 119.59 117.386 119.799C117.386 120.008 117.555 120.178 117.764 120.178Z"
        fill="#48D8F5"
      />
      <path
        d="M123.472 103.619C123.472 103.723 123.388 103.806 123.285 103.806C123.183 103.806 123.098 103.723 123.098 103.619C123.098 103.516 123.183 103.433 123.285 103.433C123.388 103.433 123.472 103.516 123.472 103.619Z"
        fill="#48D8F5"
      />
      <path
        d="M116.593 135.592C116.696 135.592 116.78 135.508 116.78 135.405C116.78 135.302 116.696 135.218 116.593 135.218C116.489 135.218 116.405 135.302 116.405 135.405C116.405 135.508 116.489 135.592 116.593 135.592Z"
        fill="#48D8F5"
      />
      <path
        d="M123.84 114.565C123.943 114.565 124.027 114.481 124.027 114.378C124.027 114.274 123.943 114.19 123.84 114.19C123.737 114.19 123.653 114.274 123.653 114.378C123.653 114.481 123.737 114.565 123.84 114.565Z"
        fill="#48D8F5"
      />
      <path
        d="M121.412 128.28C121.62 128.28 121.79 128.111 121.79 127.902C121.79 127.694 121.62 127.524 121.412 127.524C121.203 127.524 121.034 127.694 121.034 127.902C121.034 128.111 121.203 128.28 121.412 128.28Z"
        fill="#48D8F5"
      />
      <path
        d="M96.6016 117.759C96.6355 118.172 96.3294 118.535 95.9159 118.569C95.5041 118.604 95.1398 118.295 95.1059 117.882C95.0708 117.47 95.3806 117.108 95.7916 117.073C96.2055 117.039 96.5686 117.346 96.6016 117.759Z"
        fill="#48D8F5"
      />
      <path
        d="M103.608 128.49C103.644 128.902 103.336 129.266 102.922 129.298C102.51 129.333 102.148 129.025 102.114 128.612C102.078 128.2 102.386 127.837 102.799 127.803C103.211 127.769 103.575 128.076 103.608 128.49Z"
        fill="#48D8F5"
      />
      <path
        d="M99.28 106.792C99.2977 107 99.1408 107.183 98.933 107.2C98.7252 107.218 98.5443 107.062 98.5261 106.855C98.5079 106.646 98.6616 106.463 98.8715 106.447C99.0792 106.428 99.2639 106.584 99.28 106.792Z"
        fill="#48D8F5"
      />
      <path
        d="M91.7928 109.213C91.8015 109.316 91.7251 109.407 91.6239 109.416C91.5193 109.423 91.4285 109.347 91.4206 109.244C91.4119 109.141 91.4884 109.05 91.5916 109.042C91.6941 109.034 91.785 109.11 91.7928 109.213Z"
        fill="#48D8F5"
      />
      <path
        d="M101.383 134.609C101.391 134.711 101.314 134.802 101.212 134.81C101.109 134.819 101.019 134.742 101.01 134.639C101.001 134.537 101.08 134.446 101.18 134.438C101.285 134.428 101.373 134.505 101.383 134.609Z"
        fill="#48D8F5"
      />
      <path
        d="M96.3813 128.707C96.3995 128.914 96.2421 129.098 96.0352 129.115C95.827 129.131 95.6448 128.977 95.6279 128.768C95.611 128.561 95.7646 128.377 95.9732 128.36C96.1802 128.343 96.3636 128.498 96.3813 128.707Z"
        fill="#48D8F5"
      />
      <path
        d="M99.6155 141.318C99.6341 141.527 99.4772 141.71 99.2706 141.726C99.0616 141.744 98.8799 141.589 98.8617 141.381C98.8464 141.174 98.9996 140.991 99.2087 140.973C99.4169 140.956 99.599 141.111 99.6155 141.318Z"
        fill="#48D8F5"
      />
      <path
        d="M95.492 147.009C95.5081 147.217 95.3536 147.4 95.1466 147.418C94.936 147.434 94.7542 147.281 94.736 147.071C94.7195 146.863 94.8752 146.681 95.0834 146.663C95.2929 146.647 95.4746 146.8 95.492 147.009Z"
        fill="#48D8F5"
      />
      <rect
        class="pin-rect"
        x="45"
        y="0"
        width="100"
        height="210"
        @click="changeShow"
        @mouseover="hovered = true"
        @mouseleave="hovered = false"
        fill="transparent"
      />
      <defs>
        <filter
          id="filter0_d"
          x="108.192"
          y="61.378"
          width="24.4014"
          height="46.5053"
          filterUnits="userSpaceOnUse"
          color-interpolation-filters="sRGB"
        >
          <feFlood flood-opacity="0" result="BackgroundImageFix" />
          <feColorMatrix
            in="SourceAlpha"
            type="matrix"
            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
            result="hardAlpha"
          />
          <feOffset dx="1.58685" dy="1.58685" />
          <feGaussianBlur stdDeviation="1.58685" />
          <feColorMatrix
            type="matrix"
            values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 0.25 0"
          />
          <feBlend
            mode="normal"
            in2="BackgroundImageFix"
            result="effect1_dropShadow"
          />
          <feBlend
            mode="normal"
            in="SourceGraphic"
            in2="effect1_dropShadow"
            result="shape"
          />
        </filter>
        <filter
          id="filter1_d"
          x="64.3747"
          y="57.0752"
          width="56.2197"
          height="24.357"
          filterUnits="userSpaceOnUse"
          color-interpolation-filters="sRGB"
        >
          <feFlood flood-opacity="0" result="BackgroundImageFix" />
          <feColorMatrix
            in="SourceAlpha"
            type="matrix"
            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
            result="hardAlpha"
          />
          <feOffset dy="6.34738" />
          <feGaussianBlur stdDeviation="3.17369" />
          <feColorMatrix
            type="matrix"
            values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 0.25 0"
          />
          <feBlend
            mode="normal"
            in2="BackgroundImageFix"
            result="effect1_dropShadow"
          />
          <feBlend
            mode="normal"
            in="SourceGraphic"
            in2="effect1_dropShadow"
            result="shape"
          />
        </filter>
        <filter
          id="filter2_d"
          x="74.533"
          y="76.6475"
          width="27.073"
          height="42.2224"
          filterUnits="userSpaceOnUse"
          color-interpolation-filters="sRGB"
        >
          <feFlood flood-opacity="0" result="BackgroundImageFix" />
          <feColorMatrix
            in="SourceAlpha"
            type="matrix"
            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
            result="hardAlpha"
          />
          <feOffset dx="1.58685" dy="1.58685" />
          <feGaussianBlur stdDeviation="1.58685" />
          <feColorMatrix
            type="matrix"
            values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 0.25 0"
          />
          <feBlend
            mode="normal"
            in2="BackgroundImageFix"
            result="effect1_dropShadow"
          />
          <feBlend
            mode="normal"
            in="SourceGraphic"
            in2="effect1_dropShadow"
            result="shape"
          />
        </filter>
        <filter
          id="filter3_d"
          x="69.7743"
          y="47.3379"
          width="44.0552"
          height="44.7594"
          filterUnits="userSpaceOnUse"
          color-interpolation-filters="sRGB"
        >
          <feFlood flood-opacity="0" result="BackgroundImageFix" />
          <feColorMatrix
            in="SourceAlpha"
            type="matrix"
            values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
            result="hardAlpha"
          />
          <feOffset dy="6.34738" />
          <feGaussianBlur stdDeviation="3.17369" />
          <feColorMatrix
            type="matrix"
            values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 0.25 0"
          />
          <feBlend
            mode="normal"
            in2="BackgroundImageFix"
            result="effect1_dropShadow"
          />
          <feBlend
            mode="normal"
            in="SourceGraphic"
            in2="effect1_dropShadow"
            result="shape"
          />
        </filter>
        <filter
          id="filter4_f"
          x="49.5692"
          y="39.1465"
          width="48.6136"
          height="55.2044"
          filterUnits="userSpaceOnUse"
          color-interpolation-filters="sRGB"
        >
          <feFlood flood-opacity="0" result="BackgroundImageFix" />
          <feBlend
            mode="normal"
            in="SourceGraphic"
            in2="BackgroundImageFix"
            result="shape"
          />
          <feGaussianBlur stdDeviation="0.5" result="effect1_foregroundBlur" />
        </filter>
        <filter
          id="filter5_f"
          x="77.9584"
          y="16.4287"
          width="33.6282"
          height="73.7426"
          filterUnits="userSpaceOnUse"
          color-interpolation-filters="sRGB"
        >
          <feFlood flood-opacity="0" result="BackgroundImageFix" />
          <feBlend
            mode="normal"
            in="SourceGraphic"
            in2="BackgroundImageFix"
            result="shape"
          />
          <feGaussianBlur stdDeviation="1" result="effect1_foregroundBlur" />
        </filter>
        <radialGradient
          id="paint0_radial"
          cx="0"
          cy="0"
          r="1"
          gradientUnits="userSpaceOnUse"
          gradientTransform="translate(109.05 163.5) scale(93.9502 31.735)"
        >
          <stop stop-color="#44FFFF" />
          <stop offset="0.265455" stop-color="#44FFFF" />
          <stop offset="1" stop-color="#44FFFF" stop-opacity="0" />
        </radialGradient>
        <linearGradient
          id="paint1_linear"
          x1="65.7631"
          y1="184.234"
          x2="107.061"
          y2="113.357"
          gradientUnits="userSpaceOnUse"
        >
          <stop stop-color="#4657C1" />
          <stop offset="0.535257" stop-color="#F757FF" />
          <stop offset="1" stop-color="#4657C0" />
        </linearGradient>
        <linearGradient
          id="paint2_linear"
          x1="37.7116"
          y1="82.964"
          x2="128.376"
          y2="190.193"
          gradientUnits="userSpaceOnUse"
        >
          <stop stop-color="#002789" />
          <stop offset="0.18629" stop-color="#002C8A" />
          <stop offset="0.352961" stop-color="#000022" stop-opacity="0" />
          <stop offset="0.5613" stop-color="#005E98" />
          <stop offset="0.738387" stop-color="#000C3D" stop-opacity="0" />
          <stop offset="0.88" stop-color="#0084A1" />
          <stop offset="0.9301" stop-color="#00C2D7" />
          <stop offset="1" stop-color="#00FFFF" />
        </linearGradient>
        <linearGradient
          id="paint3_linear"
          x1="74.9732"
          y1="176.567"
          x2="106.15"
          y2="122.165"
          gradientUnits="userSpaceOnUse"
        >
          <stop stop-color="#4657C1" />
          <stop offset="0.535257" stop-color="#F757FF" />
          <stop offset="1" stop-color="#4657C0" />
        </linearGradient>
        <linearGradient
          id="paint4_linear"
          x1="53.2638"
          y1="99.4801"
          x2="122.078"
          y2="182.226"
          gradientUnits="userSpaceOnUse"
        >
          <stop stop-color="#002789" />
          <stop offset="0.18629" stop-color="#002C8A" />
          <stop offset="0.352961" stop-color="#000022" stop-opacity="0" />
          <stop offset="0.5613" stop-color="#005E98" />
          <stop offset="0.738387" stop-color="#000C3D" stop-opacity="0" />
          <stop offset="0.88" stop-color="#0084A1" />
          <stop offset="0.9301" stop-color="#00C2D7" />
          <stop offset="1" stop-color="#00FFFF" />
        </linearGradient>
        <linearGradient
          id="paint5_linear"
          x1="109.961"
          y1="-6.47806"
          x2="109.961"
          y2="164.702"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.325214" stop-color="#FFDEDE" stop-opacity="0" />
          <stop offset="1" stop-color="#BFFFF7" stop-opacity="0.72" />
        </linearGradient>
        <linearGradient
          id="paint6_linear"
          x1="107.5"
          y1="47.8863"
          x2="107.5"
          y2="174.119"
          gradientUnits="userSpaceOnUse"
        >
          <stop stop-color="white" stop-opacity="0" />
          <stop offset="1" stop-color="#00FFF0" />
        </linearGradient>
        <linearGradient
          id="paint7_linear"
          x1="110.067"
          y1="1.89156"
          x2="110.068"
          y2="164.129"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.325214" stop-color="#FBA4A4" stop-opacity="0" />
          <stop offset="1" stop-color="#00FFE0" />
        </linearGradient>
        <linearGradient
          id="paint8_linear"
          x1="110.961"
          y1="-8.47806"
          x2="110.961"
          y2="162.702"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.325214" stop-color="#FFDEDE" stop-opacity="0" />
          <stop offset="1" stop-color="#BFFFF7" stop-opacity="0.72" />
        </linearGradient>
        <radialGradient
          id="paint9_radial"
          cx="0"
          cy="0"
          r="1"
          gradientUnits="userSpaceOnUse"
          gradientTransform="translate(107 157.5) scale(31.9999 17.25)"
        >
          <stop offset="0.0622" stop-color="#FF0000" />
          <stop offset="0.0661" stop-color="#FA0000" />
          <stop offset="0.468749" stop-color="#CC0000" />
          <stop offset="0.921875" />
        </radialGradient>
        <linearGradient
          id="paint10_linear"
          x1="124.528"
          y1="128.392"
          x2="237.766"
          y2="-10.2764"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.141556" stop-color="#19AB65" />
          <stop offset="0.439653" stop-color="#7344D7" />
          <stop offset="1" stop-color="#00369F" />
        </linearGradient>
        <linearGradient
          id="paint11_linear"
          x1="118.89"
          y1="109.461"
          x2="144.798"
          y2="87.1749"
          gradientUnits="userSpaceOnUse"
        >
          <stop stop-color="#830936" />
          <stop offset="1" stop-color="#E664E0" />
        </linearGradient>
        <linearGradient
          id="paint12_linear"
          x1="67.1854"
          y1="-1.81204"
          x2="24.5277"
          y2="59.4251"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#9F19AB" />
          <stop offset="0.359375" stop-color="#25B176" />
          <stop offset="0.677083" stop-color="#E91061" />
          <stop offset="1" stop-color="#E664E0" />
        </linearGradient>
        <linearGradient
          id="paint13_linear"
          x1="100.224"
          y1="-13.3539"
          x2="91.3869"
          y2="68.9784"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#9F19AB" />
          <stop offset="0.359375" stop-color="#25B176" />
          <stop offset="0.677083" stop-color="#4E35E4" />
          <stop offset="1" stop-color="#E664E0" />
        </linearGradient>
        <linearGradient
          id="paint14_linear"
          x1="83.0223"
          y1="99.8289"
          x2="99.7804"
          y2="-10.1795"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#19AB65" />
          <stop offset="0.046509" stop-color="#3716FF" />
          <stop offset="0.52027" stop-color="#B144D7" />
          <stop offset="1" stop-color="#FF63CE" />
        </linearGradient>
        <linearGradient
          id="paint15_linear"
          x1="125.59"
          y1="103.18"
          x2="110.515"
          y2="68.0029"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#AA2163" />
          <stop offset="0.2257" stop-color="#D30F6D" />
          <stop offset="0.727364" stop-color="#CE6698" />
          <stop offset="1" stop-color="#F7A3CC" />
        </linearGradient>
        <linearGradient
          id="paint16_linear"
          x1="137.216"
          y1="64.7561"
          x2="129.146"
          y2="83.2435"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#AA2163" />
          <stop offset="0.2257" stop-color="#C8347B" />
          <stop offset="0.506326" stop-color="#D30F6D" />
          <stop offset="1" stop-color="#F7A3CC" />
        </linearGradient>
        <linearGradient
          id="paint17_linear"
          x1="101.06"
          y1="114.925"
          x2="53.6333"
          y2="69.3755"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#AA2163" />
          <stop offset="0.2257" stop-color="#D30F6D" />
          <stop offset="0.5946" stop-color="#CE6698" />
          <stop offset="1" stop-color="#F7A3CC" />
        </linearGradient>
        <linearGradient
          id="paint18_linear"
          x1="98.221"
          y1="101.296"
          x2="78.9617"
          y2="95.7563"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#AA2163" />
          <stop offset="0.2257" stop-color="#D30F6D" />
          <stop offset="0.5946" stop-color="#CE6698" />
          <stop offset="1" stop-color="#F7A3CC" />
        </linearGradient>
        <radialGradient
          id="paint19_radial"
          cx="0"
          cy="0"
          r="1"
          gradientUnits="userSpaceOnUse"
          gradientTransform="translate(101 130) rotate(-99.3602) scale(46.114 38.006)"
        >
          <stop offset="0.359375" stop-color="#8FFFFF" />
          <stop offset="1" stop-color="#E664E0" stop-opacity="0" />
        </radialGradient>
        <linearGradient
          id="paint20_linear"
          x1="79.7959"
          y1="57.5236"
          x2="73.7214"
          y2="67.9942"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#AA2163" />
          <stop offset="0.2257" stop-color="#D30F6D" />
          <stop offset="0.5946" stop-color="#CE6698" />
          <stop offset="1" stop-color="#F7A3CC" />
        </linearGradient>
        <linearGradient
          id="paint21_linear"
          x1="98.23"
          y1="55.5214"
          x2="107.877"
          y2="59.5147"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#AA2163" />
          <stop offset="0.2257" stop-color="#C8347B" />
          <stop offset="0.5946" stop-color="#CE6698" />
          <stop offset="1" stop-color="#F7A3CC" />
        </linearGradient>
        <linearGradient
          id="paint22_linear"
          x1="90.8078"
          y1="60.6728"
          x2="80.2135"
          y2="53.7177"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#AA2163" />
          <stop offset="0.2257" stop-color="#D30F6D" />
          <stop offset="0.5946" stop-color="#CE6698" />
          <stop offset="1" stop-color="#F7A3CC" />
        </linearGradient>
        <linearGradient
          id="paint23_linear"
          x1="95.1044"
          y1="56.9392"
          x2="99.1436"
          y2="41.686"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#AA2163" />
          <stop offset="0.199617" stop-color="#D30F6D" />
          <stop offset="0.371908" stop-color="#F68EC0" />
          <stop offset="0.563307" stop-color="#CE6698" />
        </linearGradient>
        <linearGradient
          id="paint24_linear"
          x1="98.7196"
          y1="64.6762"
          x2="97.7099"
          y2="74.3731"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#AA2163" />
          <stop offset="0.2257" stop-color="#D30F6D" />
          <stop offset="0.5946" stop-color="#CE6698" />
          <stop offset="1" stop-color="#F7A3CC" />
        </linearGradient>
        <linearGradient
          id="paint25_linear"
          x1="93.8096"
          y1="60.6265"
          x2="103.878"
          y2="65.7756"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#AA2163" />
          <stop offset="0.266301" stop-color="#D30F6D" />
          <stop offset="0.624932" stop-color="#F7A3CC" />
          <stop offset="1" stop-color="#CE6698" />
        </linearGradient>
        <linearGradient
          id="paint26_linear"
          x1="89.3933"
          y1="66.4838"
          x2="102.16"
          y2="79.4503"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#AA2163" />
          <stop offset="0.2257" stop-color="#C8347B" />
          <stop offset="0.5946" stop-color="#D30F6D" />
          <stop offset="1" stop-color="#F7A3CC" />
        </linearGradient>
        <linearGradient
          id="paint27_linear"
          x1="88.1736"
          y1="62.5777"
          x2="84.1292"
          y2="73.0714"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#AA2163" />
          <stop offset="0.2257" stop-color="#C8347B" />
          <stop offset="0.564201" stop-color="#D30F6D" />
          <stop offset="1" stop-color="#CE6698" />
        </linearGradient>
        <linearGradient
          id="paint28_linear"
          x1="95.7296"
          y1="55.1055"
          x2="85.0656"
          y2="70.6419"
          gradientUnits="userSpaceOnUse"
        >
          <stop offset="0.0354" stop-color="#D30F6D" />
          <stop offset="0.2257" stop-color="#C8347B" />
          <stop offset="0.5946" stop-color="#CE6698" />
          <stop offset="1" stop-color="#CDA3F7" />
        </linearGradient>
        <radialGradient
          id="paint29_radial"
          cx="0"
          cy="0"
          r="1"
          gradientUnits="userSpaceOnUse"
          gradientTransform="translate(107.5 156) scale(25.4994 15.0004)"
        >
          <stop stop-color="#4CEAF5" />
          <stop offset="1" />
        </radialGradient>
      </defs>
    </svg>
  </div>
</template>

<script>
import AppPinPopup from "@/components/PinPopup.vue";

export default {
  name: "AppPinStart3",
  props: {
    activePin: {
      type: String,
      required: false,
    },
  },
  components: {
    AppPinPopup,
  },
  data() {
    return {
      show: false,
      hovered: false,
    };
  },
  methods: {
    changeShow() {
      this.$emit("removeActivePin", "pin10");
      this.show = !this.show;
    },
  },
  // watch: {
  //   activePin: function (oldVal, actualVal) {
  //     if (oldVal != actualVal) {
  //       console.log('watch in pin10')
  //       this.show = !this.show;
  //     }
  //   },
  // },
};
</script>

<style>
</style>