<template>
  <demo-section class="demo-field">
    <basic-usage />
    <custom-type />
    <disabled />
    <show-icon />
    <error-info />
    <insert-button />
    <format-value />
    <!-- <autosize /> -->
    <show-word-limit />
    <input-align />
  </demo-section>
</template>

<script>
import BasicUsage from './BasicUsage';
import CustomType from './CustomType';
import Disabled from './Disabled';
import ShowIcon from './ShowIcon';
import ErrorInfo from './ErrorInfo';
import InsertButton from './InsertButton';
import FormatValue from './FormatValue';
import ShowWordLimit from './ShowWordLimit';
import InputAlign from './InputAlign';

export default {
  components: {
    BasicUsage,
    CustomType,
    Disabled,
    ShowIcon,
    ErrorInfo,
    InsertButton,
    FormatValue,
    ShowWordLimit,
    InputAlign,
  },
};
</script>
