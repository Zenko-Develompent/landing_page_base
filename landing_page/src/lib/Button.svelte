<script lang="ts">
  export let label = "Button"; /*делаем кнопку реактивной за счёт let*/
</script>

<button class="Button1_primary">
  {label}
</button>

<style>
  .Button1_primary {
    width: 155px; /*ширина кнопки*/
    height: 46px; /*высота*/
    background-color: #2E64F0;/*цвет кнопки*/
    color: #fff; /*цвет текста*/

		display: inline-flex; /*делаем кнопку контейнером*/
		align-items: center; /*выравнивает по вертикали */
		justify-content: center; /*горизонтальное выравнение */
		text-align: center; /*выравнивание текста по середине в контейнере*/

		font-family: "Lexend Exa", system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif;
    font-size: 20px;
    font-weight: 400;
    line-height: 1; /*Высота блока текста по размеру шрифта*/
    white-space: nowrap; /*отмена переноса текста внутри кнопки*/

    border: none;
    border-radius: 25px;
    cursor: pointer;
    transition: background-color 0.2s;
  }
</style>
