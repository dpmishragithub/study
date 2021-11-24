<template>
  <div>
      <!-- Create By Joker Banny -->
<div class=" bg-gray-50 flex justify-center items-center py-10">
 <div class=" flex items-center justify-center px-4">
    <div class="max-full  bg-white w-full ">
        <h2 class="text-4xl text-center p-4 font-bold bg-gray-50">Apex Applicant Information</h2>
        <div class="p-4 border-b rounded-t-lg bg-red-500">
            <h2 class="text-2xl text-white">
                Basic Details
            </h2>
        
        <div class="bg-gray-50 mt-4 -mb-3 -ml-3 -mr-3">
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Select Stream <span class="text-red-600">*</span>
                </p>
                <select id="country" name="country" autocomplete="country" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                  <option>Please Select</option>
                  <option>Engineering</option>
                  <option>Medical</option>
                </select>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Current Class <span class="text-red-600">*</span>
                </p>
               <select id="country" name="country" autocomplete="country" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                  <option>Please Select</option>
                  <option>Engineering</option>
                  <option>Medical</option>
                </select>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Course Name <span class="text-red-600">*</span>
                </p>
                <select id="country" name="country" autocomplete="country" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                  <option>Please Select</option>
                  <option>Engineering</option>
                  <option>Medical</option>
                </select>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Preferred Study Medium <span class="text-red-600">*</span>
                </p>
                   <div class="mt-4 space-y-4">
                <div class="flex items-center">
                  <input id="push-everything" name="push-notifications" type="radio" class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 border-gray-300">
                  <label for="push-everything" class="ml-3 block text-sm font-medium text-gray-700">
                   English
                  </label>
                </div>
                  </div>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Study Centre Choice <span class="text-red-600">*</span>
                </p>
               <select id="country" name="country" autocomplete="country" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                  <option>Please Select</option>
                  <option>Engineering</option>
                  <option>Medical</option>
                </select>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Test Centre Choice <span class="text-red-600">*</span>
                </p>
                <select id="country" name="country" autocomplete="country" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                  <option>Please Select</option>
                  <option>Engineering</option>
                  <option>Medical</option>
                </select>
                
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Are you Bansalite?
                </p>
                  <div class="mt-4 space-y-4">
                <div class="flex items-center">
                  <input id="push-everything" name="push-notifications" type="radio" class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 border-gray-300">
                  <label for="push-everything" class="ml-3 block text-sm font-medium text-gray-700">
                   Yes
                  </label>
                  <input id="push-everything" name="push-notifications" type="radio" class="ml-6 focus:ring-indigo-500 h-4 w-4 text-indigo-600 border-gray-300">
                  <label for="push-everything" class="ml-3 block text-sm font-medium text-gray-700">
                   No
                  </label>
                </div>
                  </div>
                
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4">
                <p class="text-gray-600">
                    BC Roll No
                </p>
                 <p>
                   <input type="text" name="candidate-name" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm"/> 
                </p>
                
            </div>
        </div>
        </div>
        <!------------Personal Details----------------------->
        <div class="p-4 border-b rounded-t-lg bg-red-500 mt-2">
            <h2 class="text-2xl text-white">
                Personal Details
            </h2>
        
        <div class="bg-gray-50 mt-4 -mb-3 -ml-3 -mr-3">
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Candidate's Name <span class="text-red-600">*</span>
                </p>
                <input type="text" name="candidate-name" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm"/>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Gender <span class="text-red-600">*</span>
                </p>
               <select id="country" name="country" autocomplete="country" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                  <option>Please Select</option>
                  <option>Engineering</option>
                  <option>Medical</option>
                </select>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Date of Birth as per School <span class="text-red-600">*</span>
                </p>
                <select id="country" name="country" autocomplete="country" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                  <option>Please Select</option>
                  <option>Engineering</option>
                  <option>Medical</option>
                </select>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Nationality <span class="text-red-600">*</span>
                </p>
                <div class="mt-4 space-y-4">
                <div class="flex items-center">
                  <input id="push-everything" name="push-notifications" type="radio" class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 border-gray-300">
                  <label for="push-everything" class="ml-3 block text-sm font-medium text-gray-700">
                   Indian
                  </label>
                  <input id="push-everything" name="push-notifications" type="radio" class="ml-6 focus:ring-indigo-500 h-4 w-4 text-indigo-600 border-gray-300">
                  <label for="push-everything" class="ml-3 block text-sm font-medium text-gray-700">
                   Other
                  </label>
                </div>
                  </div>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Category <span class="text-red-600">*</span>
                </p>
               <select id="country" name="country" autocomplete="country" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                  <option>Please Select</option>
                  <option>Engineering</option>
                  <option>Medical</option>
                </select>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4">
                <p class="text-gray-600">
                    Father's Name <span class="text-red-600">*</span>
                </p>
                <input type="text" name="candidate-name" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm"/>
                
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4">
                <p class="text-gray-600">
                    Mother's Name <span class="text-red-600">*</span>
                </p>
                <input type="text" name="candidate-name" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm"/>
                
            </div>
        </div>
        </div>
        <!------------Address Details----------------------->
        <div class="p-4 border-b rounded-t-lg bg-red-500 mt-2">
            <h2 class="text-2xl text-white">
                Addresses & Contact Details
            </h2>
        
        <div class="bg-gray-50 mt-4 -mb-3 -ml-3 -mr-3">
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Address Line No. 1 <span class="text-red-600">*</span>
                </p>
                <input type="text" name="candidate-name" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm"/>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Address Line No. 2
                </p>
               <input type="text" name="candidate-name" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm"/>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    City / Town / Post / Tehsil / District <span class="text-red-600">*</span>
                </p>
                <input type="text" name="candidate-name" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm"/>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Pin Code <span class="text-red-600">*</span>
                </p>
                <p>
                    <input type="text" name="candidate-name" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm"/>
                </p>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    State Name <span class="text-red-600">*</span>
                </p>
               <select id="country" name="country" autocomplete="country" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                  <option>Please Select</option>
                  <option>Engineering</option>
                  <option>Medical</option>
                </select>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4">
                <p class="text-gray-600">
                    Mobile No <span class="text-red-600">*</span>
                </p>
                <input type="text" name="candidate-name" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm"/>
                
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4">
                <p class="text-gray-600">
                    E-Mail Address <span class="text-red-600">*</span>
                </p>
                <input type="text" name="candidate-name" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm"/>
                <!-- <p class="float-right">(Do not leave any column blank between E-Mail ID.)</p> -->
            </div>
        </div>
        </div>
         <!------------Academic Details----------------------->
         <div class="p-4 border-b rounded-t-lg bg-red-500 mt-2">
            <h2 class="text-2xl text-white">
                Academic (Qualification) Details
            </h2>
        
        <div class="bg-gray-50 mt-4 -mb-3 -ml-3 -mr-3">
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Current School Name <span class="text-red-600">*</span>
                </p>
                <input type="text" name="candidate-name" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm"/>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Current School City Name <span class="text-red-600">*</span>
                </p>
                <select id="country" name="country" autocomplete="country" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                  <option>Please Select</option>
                  <option>Engineering</option>
                  <option>Medical</option>
                </select>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Education Board <span class="text-red-600">*</span>
                </p>
                <select id="country" name="country" autocomplete="country" class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm">
                  <option>Please Select</option>
                  <option>Engineering</option>
                  <option>Medical</option>
                </select>
            </div>
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
                <p class="text-gray-600">
                    Remark 
                </p>
               <textarea class="mt-1 block w-full py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-red-500 focus:border-red-500 sm:text-sm"></textarea>
            </div>
        </div>
        </div>
         <!------------Verification----------------------->
         <div class="p-4 border-b rounded-t-lg bg-red-500 mt-2">
            <h2 class="text-2xl text-white">
                Final Submission And Verification
            </h2>
        
        <div class="bg-gray-50 mt-4 -mb-3 -ml-3 -mr-3">
            <div class="md:grid md:grid-cols-2 hover:bg-gray-50 md:space-y-0 space-y-1 p-4 border-b">
               <button class="btn">Submit</button>
               <button class="btn">Reset</button>
            </div>
        </div>
        </div>
    </div>
</div>
</div>
  </div>
</template>

<script>
export default {

   
}
</script>

<style>

</style>