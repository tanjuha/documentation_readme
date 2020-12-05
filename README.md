<div align="center">
<h1>Documentation</h1>

<p>Admin part</p>
</div>

## Contents

- [Buttons](#button)
  - [Examples](#examples)
  - [Sizes](#sizes)
- [Links](#links)
- [Tables](#tables)
  - [Table buttons top bottom](#table-buttons-top-bottom)
  - [Table forms](#table-forms)

## Button

### Examples

<img src="doc_images/buttons/examples.jpg" alt="examples" data-canonical-src="doc_images/buttons/examples.jpg" />

```
<button type="button" class="btn admin-btn-primary">primary</button>
<button type="button" class="btn admin-btn-primary-o">primary outline</button>
<button type="button" class="btn admin-btn-secondary">secondary</button>
<button type="button" class="btn admin-btn-danger">secondary</button>
<button type="button" class="btn admin-btn-link">link</button>
<button type="button" class="btn disabled" disabled >disabled</button>
<button type="button" class="btn disabled-o" disabled >disabled outline</button>

```

### Sizes

Add `.btn-sm` or `.btn-md` or `.btn-lg`

  <img src="doc_images/buttons/size_sm_md_lg.jpg" alt="sizes sm md lg" data-canonical-src="doc_images/buttons/size_sm_md_lg.jpg" />

```
<button type="button" class="btn admin-btn-primary btn-sm">primary</button>
<button type="button" class="btn admin-btn-primary-o btn-md">primary outline</button>
<button type="button" class="btn admin-btn-secondary btn-lg">secondary</button>
```

Full width add `.d-block` or `.w-100`

   <img src="doc_images/buttons/full_width.png" alt="full width" data-canonical-src="doc_images/buttons/full_width.png" />

```
<button type="button" class="btn admin-btn-danger d-block">danger</button>
<button type="button" class="btn admin-btn-danger w-100">danger</button>
```

## Links

Add `.admin-link`

 <img src="doc_images/links/link.png" alt="full width" data-canonical-src="doc_images/links/link.png" />

```
<a href="#" class="admin-link">link link</a>
```

## Tables

### Table buttons top bottom

#### Exampls

 <img src="doc_images/tables/table_btn_top_bottom.png" alt="Tables buttons top bottom" data-canonical-src="doc_images/tables/table_btn_top_bottom.png" />

```
// top left, right
    <div class="table-btn-top">
      <div class="table-btn left">
        top left
      </div>
      <div class="table-btn right">
        top right
      </div>
    </div>

// bottom left right
    <div class="table-btn-bottom">
      <div class="table-btn left">
        bottom left
      </div>
      <div class="table-btn right">
        bottom right
      </div>
    </div>
```

### Table forms

Form search

<img src="doc_images/tables/table_btn_search.png" alt="Tables button search" data-canonical-src="doc_images/tables/table_btn_search.png" />

```
  <div class="table-btn-top">
      <div class="table-btn left">
          <form class="form-inline form-search">
              <input class="form-control" type="search" placeholder="Search" aria-label="Search">
              <i class="fa fa-search"></i>
          </form>
      </div>
  </div>
```

Form date

<img src="doc_images/tables/form_date.png" alt="Form date" data-canonical-src="doc_images/tables/form_date.png" />

```
  <div class="table-btn-top">
    <div class="table-btn right d-flex">
        <form class="form-inline form-date">
            <label>Дата: </label>
            <input class="form-control ml-1" type="date">
        </form>
    </div>
  </div>
```

Form select

<img src="doc_images/tables/form_select.png" alt="Form select" data-canonical-src="doc_images/tables/form_select.png" />

```
  <div class="table-btn-top">
    <div class="table-btn right d-flex">
        <form class="form-inline form-select">
            <label>Должность: </label>
            <select class="select">
                <option selected>Должность</option>
                <option value="1">One</option>
                <option value="2">Two</option>
                <option value="3">Three</option>
            </select>
        </form>
    </div>
  </div>
```

Example form date and form select

<img src="doc_images/tables/form_date_select.png" alt="Forms date and select" data-canonical-src="doc_images/tables/form_date_select.png" />

```
  <div class="table-btn-top">
    <div class="table-btn right d-flex">
        <form class="form-inline form-date">
            <label>Дата: </label>
            <input class="form-control ml-1" type="date">
        </form>
        <form class="form-inline form-select ml-3">
            <label>Должность: </label>
            <select class="select">
                <option selected>Должность</option>
                <option value="1">One</option>
                <option value="2">Two</option>
                <option value="3">Three</option>
            </select>
        </form>
    </div>
  </div>
```