---
slug: "/checkbox-groups"
date: "2019-05-04"
title: "Elements > Checkbox-groups"
---

<!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<link rel="stylesheet" href="../../../../../../../raaghu/src/assets/css/style-elements.css">
<link rel="stylesheet" href="../../../../../../../raaghu/src/assets/css/main.css">


#### Checkbox Groups

<p class="">Checkbox group refers to the list of checkboxes referring to a particular group. Checkbox group allows multiple selections from a list. </p>
<section class="py-4">
    <h6>Default</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic-tab" data-bs-toggle="tab" data-bs-target="#PreviewBasic" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic-tab" data-bs-toggle="tab" data-bs-target="#AngularBasic" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
           <li class="nav-item" role="presentation">
            <button class="nav-link" id="Reactbasic-tab" data-bs-toggle="tab" data-bs-target="#Reactbasic" type="button" role="tab" aria-controls="Reactbasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewBasic" role="tabpanel" aria-labelledby="PreviewBasic-tab">
         <div class="contents p-5">
              <div class="row">   
                 <div class="col-md-12">
                    <img src="/images/checkbox-group-basic.png" class="img-fluid">
                 </div>                         
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
 <rds-checkbox-groups
  [switch]="false"
  [inline]="false"
  [withLabel]="true"
  [isInputGroup]="false"
  [itemList]="itemList"
  state="checkbox"
  (onCheck)="onCheck($event)"
  (onUncheck)="onUncheck($event)"
></rds-checkbox-groups>
```
</div>
</div>
  </div>
    <!-- React start -->
        <div class="tab-pane fade show" id="Reactbasic" role="tabpanel" aria-labelledby="Reactbasic-tab">
          <div class="contents bg-code">
    <div class="row m-0">

```html
<RdsCheckboxGroup
  errorMessage="Error Message"
  itemList={[
    {
      checked: false,
      disabled: false,
      id: 1,
      label: 'Child Checkbox 1'
    },
    {
      checked: false,
      disabled: false,
      id: 2,
      label: 'Child Checkbox 2'
    },
    {
      checked: false,
      disabled: false,
      id: 3,
      label: 'Child Checkbox 3'
    }
  ]}
  label="Checkbox Group"
  state="Checkbox"
/>
/>
```

</div>
          </div>
        </div>
      <!-- React End -->
        </div>
      </div>
    </div>
  </section>
  
<section class="py-4">
                        <h6>
                           Skeleton / Specifications
                        </h6>
                        <div class="py-3">
                              <!-- Tab panes -->
                              <div class="card border p-5">
                                 <div class="row">
                                    <div class="col-md-12">
                                       <img src="/images/checkbox-group-skeleton.png" class="img-fluid">
                                    </div>
                                 </div>
                              </div>
                        </div>
</section>
