# levus-filter
Фільтрація товарів на сторінці

<aside id="aside" role="complementary">
    <p>- Ціна</p>
    <div id="filter">
        <div id="plusminus">
            <input type="text" id="filter-min">
            <input type="text" id="filter-max">	
        </div>
        <div id="range">
            <input type="range" id="filter-left">
            <input type="range" id="filter-right">
        </div>
    </div>
    <!-- #filter -->
    <hr>
    <p>- Бренд</p>
    <div id="brand-select">
        <select id="filter-brands">
            <option value=""></option>
            <option value="brand-1">Адідас</option>
            <option value="brand-2">Пума</option>
            <option value="brand-3">Найкі</option>
            <option value="brand-4">Рібок</option>
        </select>
        <!-- #filter-brands -->                        
    </div>
    <!-- #brand-select -->
    <hr>
    <p>- Колір</p>
    <div id="color-select">
        <select id="filter-colors">
            <option value=""></option>
            <option value="color-1">Колір 1</option>
            <option value="color-2">Колір 2</option>
            <option value="color-3">Колір 3</option>
            <option value="color-4">Колір 4</option>
        </select>
        <!-- #filter-brands -->                        
    </div>
    <!-- #brand-select -->  
    <hr> 
    <p>- Характеристики</p>
    <div id="features">
        <label>
            <input type="checkbox" value="f1"> характеристка - f1
        </label>
        <label value="f2">
            <input type="checkbox" value="f2"> характеристка - f2
        </label>
        <label>
            <input type="checkbox" value="f3"> характеристка - f3
        </label>
        <label>
            <input type="checkbox" value="f4"> характеристка - f4
        </label>
        <label>
            <input type="checkbox" value="f5"> характеристка - f5
        </label>
        <label>
            <input type="checkbox" value="f6"> характеристка - f6
        </label>
    </div>
    <!-- #features -->
    <hr>
    <p>- Розміри</p>
    <div id="sizes">
        <label>
            <input type="checkbox" value="100*100"> розмір 100*100
        </label>
        <label>
            <input type="checkbox" value="200*100"> розмір 200*100
        </label>
        <label>
            <input type="checkbox" value="300*100"> розмір 300*100
        </label>
        <label>
            <input type="checkbox" value="400*100"> розмір 400*100
        </label>
        <label>
            <input type="checkbox" value="500*100"> розмір 500*100
        </label>
    </div>
    <!-- #sizes -->
    <hr>
</aside>
<!-- #aside -->