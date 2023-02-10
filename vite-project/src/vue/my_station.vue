<template>
    <div class="bg-black w-100% h-screen flex justify-center">
      <div class="bg-white w-100% h-screen container">
        <div class="flex flex-row w-full p-4 justify-between items-center">
  
          <div class="flex gap-1 items-center">
            <label class="text-xl">My Station</label>
            <label class="text-gray-500">1 แห่ง</label>
          </div>
  
          <button class="bg-blue-500 text-white flex p-1 gap-1">
            <span>+</span>
            <label>Register new station</label>
          </button>
  
        </div>
        <hr class="mb-2 mt-2"/>
        <div class="bg-gray-200 flex w-full flex-row">
          <div class="bg-black flex p-2 w-1/3">
            <div class="w-full h-full bg-gray-50"></div>
          </div>
          <div class="bg-yellow-800 flex flex-col w-2/3">
              <div class="bg-blue-500 flex flex-col p-4 w-full">
                <label class="text-2xl max-md:text-base">ข้อมูลสถานที่</label>
                <label class="max-md:text-sm">บ้านเลขที่ xxx/xxx จ.ชลบุรี อ.ศรีราชา ต.ทุ่งสุขลา 20xxx</label>
              </div>
              <div class="bg-black flex flex-col p-2 w-full text-blue-400">
                <button class="text-blue-500">
                  <label>Edit Station</label>
                </button>
              </div>
          </div>
        </div>
      
        <div class="px-4 overflow-auto">
          <table class="table-auto w-full text-left">
            <thead>
              <tr class="bg-gray-800 text-white">
                <th class="px-4 py-2">No.</th>
                <th class="px-4 py-2">Type</th>
                <th class="px-4 py-2">Rate</th>
                <th class="px-4 py-2">status</th>
                <th class="px-4 py-2">Request</th>
                <th class="px-4 py-2">customer-Request</th>
              </tr>
            </thead>
          <tbody>
            <tr class="bg-gray-100">
              <td class="border px-4 py-2">Row 1, Column 1</td>
              <td class="border px-4 py-2">Row 1, Column 2</td>
              <td class="border px-4 py-2">Row 1, Column 3</td>
              <td class="border px-4 py-2">Row 1, Column 4</td>
              <td class="border px-4 py-2">Row 1, Column 5</td>
              <td class="border px-4 py-2">Row 1, Column 6</td>
            </tr>
            <tr class="bg-gray-200">
              <td class="border px-4 py-2">Row 2, Column 1</td>
              <td class="border px-4 py-2">Row 2, Column 2</td>
              <td class="border px-4 py-2">Row 2, Column 3</td>
              <td class="border px-4 py-2">Row 2, Column 4</td>
              <td class="border px-4 py-2">Row 2, Column 5</td>
              <td class="border px-4 py-2">Row 2, Column 6</td>
            </tr>
          </tbody>
          </table>
        </div>
      </div>
  
    </div>
  </template>
  
  
  <!-- md =tablet
  max-md= น้อยกว่า tablet
  max-lg = น้อยกว่าคอม
  lg =คอม
  sm =โทรศัพท์ -->