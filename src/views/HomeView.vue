<template>
  <main>
    <section class="bg-black p-5"></section>
    <section class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
      <div class="banner pt-5">
        <div
          class="bg-cover bg-no-repeat bg-center h-[400px] relative"
          style="background-image: url(/src/assets/imager/banner.png)"
        >
          <h2 class="absolute bottom-0 p-7 text-white text-3xl">窩窩家居<br />跟您一起品味生活</h2>
        </div>
      </div>
    </section>
    <section class="mx-auto max-w-7xl px-2 pt-6 sm:px-6 lg:px-8">
      <h2 class="text-3xl text-center mb-5">床墊優勢</h2>
      <div class="flex flex-col md:flex-row">
        <div class="basis-1/3 flex flex-col justify-center">
          <img
            src="../assets/imager/photo-1582282577230-2f59c636e60b.png"
            alt="woodImg"
            class="px-3"
          />
          <h5 class="text-center font-bold py-3">原木料環保</h5>
        </div>
        <div class="basis-1/3 flex flex-col justify-center">
          <img
            src="../assets/imager/photo-1560164301-6ac46d2d61c4.png"
            alt="woodImg"
            class="px-3"
          />
          <h5 class="text-center font-bold py-3">好收納</h5>
        </div>
        <div class="basis-1/3 flex flex-col justify-center">
          <img
            src="../assets/imager/photo-1560846389-e4e6d764cd61.png"
            alt="woodImg"
            class="px-3"
          />
          <h5 class="text-center font-bold py-3">好組裝</h5>
        </div>
      </div>
    </section>
    <section class="bg-gray-200">
      <div class="mx-auto max-w-7xl px-2 py-6 sm:px-6 lg:px-8">
        <h2 class="text-3xl text-center py-6">家具比較</h2>
        <div class="w-full xl:w-9/12 px-4 mx-auto">
          <table class="table-auto w-full">
            <thead>
              <tr>
                <th class="align-middle"></th>
                <th class="align-middle text-xl">窩窩系統模組家具</th>
                <th class="align-middle text-xl text-gray-400">組合式家具</th>
                <th class="align-middle text-xl text-gray-400">實木家具</th>
              </tr>
            </thead>
            <tbody>
              <tr class="border-y-2 border-gray-400">
                <td class="py-3">
                  <div class="flex justify-center">
                    <h6 class="font-bold text-xl">可單人自行組裝</h6>
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <img src="../assets/checklg.svg" alt="checklg" />
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <h6 class="text-gray-400">不一定</h6>
                  </div>
                </td>
                <td class="py-3"></td>
              </tr>
              <tr class="border-y-2 border-gray-400">
                <td class="py-3">
                  <div class="flex justify-center">
                    <h6 class="font-bold text-xl">可多次重複拆裝</h6>
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <img src="../assets/checklg.svg" alt="checklg" />
                  </div>
                </td>
                <td class="py-3"></td>
                <td class="py-3"></td>
              </tr>
              <tr class="border-y-2 border-gray-400">
                <td class="py-3">
                  <div class="flex justify-center">
                    <h6 class="font-bold text-xl">床墊規格彈性大</h6>
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <img src="../assets/checklg.svg" alt="checklg" />
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <h6 class="text-gray-400">不一定</h6>
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <h6 class="text-gray-400">不一定</h6>
                  </div>
                </td>
              </tr>
              <tr class="border-y-2 border-gray-400">
                <td class="py-3">
                  <div class="flex justify-center">
                    <h6 class="font-bold text-xl">材質可長久使用</h6>
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <img src="../assets/checklg.svg" alt="checklg" />
                  </div>
                </td>
                <td class="py-3"></td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <img src="../assets/checklg.svg" alt="checklg" />
                  </div>
                </td>
              </tr>
              <tr class="border-y-2 border-gray-400">
                <td class="py-3">
                  <div class="flex justify-center">
                    <h6 class="font-bold text-xl">小客車即可搬運</h6>
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <img src="../assets/checklg.svg" alt="checklg" />
                  </div>
                </td>
                <td class="py-3"></td>
                <td class="py-3"></td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </section>
    <section class="bg-purple-600">
      <div class="mx-auto max-w-7xl px-2 py-6 sm:px-6 lg:px-8">
        <h2 class="text-3xl text-center text-white font-bold mb-6">好評推薦</h2>
        <ul class="flex justify-center overflow-x-auto">
          <li class="basis-1/3 px-5">
            <div class="flex bg-white">
              <div class="basis-1/3">
                <img
                  src="../assets/imager/product/photo-1576354302919-96748cb8299e.png"
                  alt="product01"
                />
              </div>
              <div class="p-3 flex flex-col">
                <div class="flex">
                  <img src="../assets/imager/user/Ellipse.png" alt="Ellipse" class="img-fluid" />
                  <div class="flex flex-col px-2">
                    <h4 class="font-bold">王六角</h4>
                    <span class="font-bold text-purple-500">Jodan 雙人床架</span>
                  </div>
                </div>
                <h4 class="text-xl font-bold pt-2">CP值很高。</h4>
              </div>
            </div>
          </li>
          <li class="basis-1/3 px-5">
            <div class="flex bg-white">
              <div class="basis-1/3">
                <img
                  src="../assets/imager/product/photo-1576354302919-96748cb8299e.png"
                  alt="product01"
                />
              </div>
              <div class="p-3 flex flex-col">
                <div class="flex">
                  <img src="../assets/imager/user/Ellipse.png" alt="Ellipse" class="img-fluid" />
                  <div class="flex flex-col px-2">
                    <h4 class="font-bold">王六角</h4>
                    <span class="font-bold text-purple-500">Jodan 雙人床架</span>
                  </div>
                </div>
                <h4 class="text-xl font-bold pt-2">CP值很高。</h4>
              </div>
            </div>
          </li>
          <li class="basis-1/3 px-5">
            <div class="flex bg-white">
              <div class="basis-1/3">
                <img
                  src="../assets/imager/product/photo-1576354302919-96748cb8299e.png"
                  alt="product01"
                />
              </div>
              <div class="p-3 flex flex-col">
                <div class="flex">
                  <img src="../assets/imager/user/Ellipse.png" alt="Ellipse" class="img-fluid" />
                  <div class="flex flex-col px-2">
                    <h4 class="font-bold">王六角</h4>
                    <span class="font-bold text-purple-500">Jodan 雙人床架</span>
                  </div>
                </div>
                <h4 class="text-xl font-bold pt-2">CP值很高。</h4>
              </div>
            </div>
          </li>
        </ul>
        <ul class="flex justify-center pt-3 overflow-x-auto">
          <li class="basis-1/3 px-5">
            <div class="flex bg-white">
              <div class="basis-1/3">
                <img
                  src="../assets/imager/product/photo-1576354302919-96748cb8299e.png"
                  alt="product01"
                />
              </div>
              <div class="p-3 flex flex-col">
                <div class="flex">
                  <img src="../assets/imager/user/Ellipse.png" alt="Ellipse" class="img-fluid" />
                  <div class="flex flex-col px-2">
                    <h4 class="font-bold">王六角</h4>
                    <span class="font-bold text-purple-500">Jodan 雙人床架</span>
                  </div>
                </div>
                <h4 class="text-xl font-bold pt-2">CP值很高。</h4>
              </div>
            </div>
          </li>
          <li class="basis-1/3 px-5">
            <div class="flex bg-white">
              <div class="basis-1/3">
                <img
                  src="../assets/imager/product/photo-1576354302919-96748cb8299e.png"
                  alt="product01"
                />
              </div>
              <div class="p-3 flex flex-col">
                <div class="flex">
                  <img src="../assets/imager/user/Ellipse.png" alt="Ellipse" class="img-fluid" />
                  <div class="flex flex-col px-2">
                    <h4 class="font-bold">王六角</h4>
                    <span class="font-bold text-purple-500">Jodan 雙人床架</span>
                  </div>
                </div>
                <h4 class="text-xl font-bold pt-2">CP值很高。</h4>
              </div>
            </div>
          </li>
          <li class="basis-1/3 px-5">
            <div class="flex bg-white">
              <div class="basis-1/3">
                <img
                  src="../assets/imager/product/photo-1576354302919-96748cb8299e.png"
                  alt="product01"
                />
              </div>
              <div class="p-3 flex flex-col">
                <div class="flex">
                  <img src="../assets/imager/user/Ellipse.png" alt="Ellipse" class="img-fluid" />
                  <div class="flex flex-col px-2">
                    <h4 class="font-bold">王六角</h4>
                    <span class="font-bold text-purple-500">Jodan 雙人床架</span>
                  </div>
                </div>
                <h4 class="text-xl font-bold pt-2">CP值很高。</h4>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </section>
    <section class="mx-auto max-w-7xl px-2 pt-6 sm:px-6 lg:px-8">
      <h2 class="text-3xl font-bold text-center pb-5">運送方式</h2>
      <div class="flex justify-center flex-col md:flex-row">
        <div class="basis-1/2 flex justify-center py-8 md:py-0">
          <div class="w-[115px] flex flex-col relative shipping">
            <div
              class="border-4 border-black rounded-full w-[115px] h-[115px] flex justify-center items-center"
            >
              <i class="bi bi-cart2 text-7xl"></i>
            </div>
            <h4 class="text-3xl font-bold text-center">STEP.1</h4>
            <p class="text-center">選購商品</p>
          </div>
        </div>
        <div class="basis-1/2 flex justify-center py-8 md:py-0">
          <div class="w-[115px] flex flex-col relative shipping">
            <div
              class="border-4 border-black rounded-full w-[115px] h-[115px] flex justify-center items-center"
            >
              <i class="bi bi-list-ul text-7xl"></i>
            </div>
            <h4 class="text-3xl font-bold text-center">STEP.2</h4>
            <p class="text-center">填寫預定資料</p>
          </div>
        </div>
        <div class="basis-1/2 flex justify-center py-8 md:py-0">
          <div class="w-[115px] flex flex-col relative shipping">
            <div
              class="border-4 border-black rounded-full w-[115px] h-[115px] flex justify-center items-center"
            >
              <i class="bi bi-check-lg text-7xl"></i>
            </div>
            <h4 class="text-3xl font-bold text-center">STEP.3</h4>
            <p class="text-center">預定成功</p>
          </div>
        </div>
        <div class="basis-1/2 flex justify-center py-8 md:py-0">
          <div class="w-[115px] flex flex-col">
            <div
              class="border-4 border-black rounded-full w-[115px] h-[115px] flex justify-center items-center"
            >
              <i class="bi bi-envelope-fill text-7xl"></i>
            </div>
            <h4 class="text-3xl font-bold text-center">STEP.4</h4>
            <p class="text-center">Email 付款資訊</p>
          </div>
        </div>
      </div>
    </section>
    <section class="mx-auto max-w-7xl px-2 py-6 sm:px-6 lg:px-8">
      <div class="inline-block relative w-64 mb-4">
        <select
          class="block appearance-none w-full bg-white border border-gray-400 hover:border-gray-500 px-4 py-2 pr-8 rounded shadow leading-tight focus:outline-none focus:shadow-outline"
        >
          <option selected>全部</option>
          <option>床架</option>
          <option>收納</option>
          <option>窗簾</option>
        </select>
        <div
          class="pointer-events-none absolute inset-y-0 right-0 flex items-center px-2 text-gray-700"
        >
          <svg class="fill-current h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
            <path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z" />
          </svg>
        </div>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-4 grid-flow-row gap-4">
        <div class="flex flex-col relative">
          <div
            class="bg-black text-white py-3 px-5 w-[88px] absolute top-[15px] right-[-5px] text-center"
          >
            新品
          </div>
          <img src="../assets/imager/product/photo-1576354302919-96748cb8299e.png" alt="" />
          <button type="button" class="btn bg-black rounded-none hover:bg-gray-700">
            加入購物車
          </button>
          <h5 class="text-xl font-bold">Antony 雙人床架／雙人加大</h5>
          <h6 class="line-through">NT$18,000</h6>
          <h4 class="font-bold text-2xl">NT$12,000</h4>
        </div>
        <div class="flex flex-col">
          <img src="../assets/imager/product/photo-1576354302919-96748cb8299e.png" alt="" />
          <button type="button" class="btn bg-black rounded-none hover:bg-gray-700">
            加入購物車
          </button>
          <h5 class="text-xl font-bold">Antony 雙人床架／雙人加大</h5>
          <h6 class="line-through">NT$18,000</h6>
          <h4 class="font-bold text-2xl">NT$12,000</h4>
        </div>
        <div class="flex flex-col">
          <img src="../assets/imager/product/photo-1576354302919-96748cb8299e.png" alt="" />
          <button type="button" class="btn bg-black rounded-none hover:bg-gray-700">
            加入購物車
          </button>
          <h5 class="text-xl font-bold">Antony 雙人床架／雙人加大</h5>
          <h6 class="line-through">NT$18,000</h6>
          <h4 class="font-bold text-2xl">NT$12,000</h4>
        </div>
        <div class="flex flex-col">
          <img src="../assets/imager/product/photo-1576354302919-96748cb8299e.png" alt="" />
          <button type="button" class="btn bg-black rounded-none hover:bg-gray-700">
            加入購物車
          </button>
          <h5 class="text-xl font-bold">Antony 雙人床架／雙人加大</h5>
          <h6 class="line-through">NT$18,000</h6>
          <h4 class="font-bold text-2xl">NT$12,000</h4>
        </div>
        <div class="flex flex-col">
          <img src="../assets/imager/product/photo-1576354302919-96748cb8299e.png" alt="" />
          <button type="button" class="btn bg-black rounded-none hover:bg-gray-700">
            加入購物車
          </button>
          <h5 class="text-xl font-bold">Antony 雙人床架／雙人加大</h5>
          <h6 class="line-through">NT$18,000</h6>
          <h4 class="font-bold text-2xl">NT$12,000</h4>
        </div>
      </div>
    </section>
    <section class="bg-gray-200">
      <div class="mx-auto max-w-7xl px-2 py-6 sm:px-6 lg:px-8">
        <h2 class="text-3xl text-center py-6">我的購物車</h2>
        <div class="w-full xl:w-9/12 px-4 mx-auto">
          <table class="table-auto w-full">
            <thead>
              <tr>
                <th class="align-middle text-start">品項</th>
                <th class="align-middle text-xl">單價</th>
                <th class="align-middle text-xl text-gray-400">數量</th>
                <th class="align-middle text-xl text-gray-400">金額</th>
                <th class="align-middle text-xl"></th>
              </tr>
            </thead>
            <tbody>
              <tr class="border-y-2 border-gray-400">
                <td class="py-3">
                  <div class="flex items-center">
                    <img
                      src="../assets/imager/product/photo-1576354302919-96748cb8299e.png"
                      alt=""
                      class="w-[80px]"
                    />
                    <h5 class="font-bold px-2">Antony 雙人床架／雙人加大</h5>
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <h5 class="font-bold">NT$12,000</h5>
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <h5 class="font-bold">1</h5>
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <h5 class="font-bold">NT$12,000</h5>
                  </div>
                </td>
                <td class="py-3">
                  <button type="button"><i class="bi bi-x-lg"></i></button>
                </td>
              </tr>
              <tr class="border-y-2 border-gray-400">
                <td class="py-3">
                  <div class="flex items-center">
                    <img
                      src="../assets/imager/product/photo-1576354302919-96748cb8299e.png"
                      alt=""
                      class="w-[80px]"
                    />
                    <h5 class="font-bold px-2">Antony 雙人床架／雙人加大</h5>
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <h5 class="font-bold">NT$12,000</h5>
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <h5 class="font-bold">1</h5>
                  </div>
                </td>
                <td class="py-3">
                  <div class="flex justify-center">
                    <h5 class="font-bold">NT$12,000</h5>
                  </div>
                </td>
                <td class="py-3">
                  <button type="button"><i class="bi bi-x-lg"></i></button>
                </td>
              </tr>
            </tbody>
            <tfoot>
              <tr>
                <th colspan="3" scope="row">
                  <div class="flex py-3">
                    <button type="button" class="btn text-black hover:bg-red-800 hover:text-white">
                      刪除所有品項
                    </button>
                  </div>
                </th>
                <th>總金額</th>
                <th>NT$13,980</th>
              </tr>
            </tfoot>
          </table>
        </div>
      </div>
    </section>
    <section class="mx-auto max-w-7xl px-2 py-6 sm:px-6 lg:px-8">
      <h2 class="text-3xl text-center py-6">填寫預訂資料</h2>
      <div class="flex justify-center">
        <form class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4 w-2/4">
          <div class="mb-4">
            <label class="block text-gray-700 text-sm font-bold mb-2" for="username">
              Username
            </label>
            <input
              class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"
              id="username"
              type="text"
              placeholder="Username"
            />
          </div>
          <div class="mb-6">
            <label class="block text-gray-700 text-sm font-bold mb-2" for="password">
              Password
            </label>
            <input
              class="shadow appearance-none border border-red-500 rounded w-full py-2 px-3 text-gray-700 mb-3 leading-tight focus:outline-none focus:shadow-outline"
              id="password"
              type="password"
              placeholder="******************"
            />
            <p class="text-red-500 text-xs italic">Please choose a password.</p>
          </div>
          <div class="flex items-center justify-between">
            <button
              class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline"
              type="button"
            >
              Sign In
            </button>
            <a
              class="inline-block align-baseline font-bold text-sm text-blue-500 hover:text-blue-800"
              href="#"
            >
              Forgot Password?
            </a>
          </div>
        </form>
      </div>
    </section>
  </main>
</template>

<script setup></script>
