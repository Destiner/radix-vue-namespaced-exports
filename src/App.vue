<template>
  <div :style="{ display: 'flex', alignItems: 'center' }">
    <label>
      <CheckboxRoot v-model:checked="checkboxOne">
        <CheckboxIndicator class="CheckboxIndicator">
          <Icon icon="radix-icons:check" />
        </CheckboxIndicator>
      </CheckboxRoot>
      <span class="Label">Accept terms and conditions.</span>
    </label>
  </div>
  <div :style="{ display: 'flex', alignItems: 'center' }">
    <label>
      <Checkbox.Root v-model:checked="checkboxOne">
        <Checkbox.Indicator class="CheckboxIndicator">
          <Icon icon="radix-icons:check" />
        </Checkbox.Indicator>
      </Checkbox.Root>
      <span class="Label">Accept terms and conditions.</span>
    </label>
  </div>
</template>

<script setup lang="ts">
import { CheckboxIndicator, CheckboxRoot } from "radix-vue";
import { Checkbox } from "radix-vue/namespaced";
</script>
