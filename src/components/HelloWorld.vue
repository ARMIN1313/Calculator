<template>
  <div>
    <table id="calculator" dir="ltr" style="text-align:center;margin: auto"> </table>
    <tr>
      <!--table row-->
      <td colspan="5">
      <!--span-->
      <input
      v-model="screen"
      dir="ltr"
      type="number"
      id="result"
      style="padding:5px;font-wright:bold; tex-align:right"
      />
      </td>
    </tr>
  </div>
</template>