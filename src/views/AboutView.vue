<script setup></script>

<template>
    <div class=" bg-slate-50 px-7 pt-8 min-h-full">
        <h2
            class="md:text-7xl text-5xl text-center md:text-start px-4 py-4 mb-4 font-semibold text-slate-600 bg-slate-200">
            About Page</h2>
        <transition appear name="fade">
            <p class="py-8 px-4 text-lg text-slate-600 text-justify bg-slate-100">Lorem ipsum dolor sit amet consectetur
                adipisicing elit. Rerum possimus
                praesentium saepe!
                Illum itaque ex
                temporibus expedita vitae fuga quaerat eum blanditiis. Molestiae ipsum architecto pariatur, modi nisi
                culpa
                qui eligendi aliquid sint inventore officia, non id doloribus accusantium vel eum dolorum, esse impedit
                beatae. Sit cum repellendus dolore tenetur autem nihil magnam similique repellat quos animi numquam
                repudiandae reprehenderit, quisquam nostrum. Repellendus totam at dignissimos perferendis nulla dicta
                suscipit optio eligendi aliquam consequatur tempore eius molestias molestiae possimus voluptatibus,
                mollitia
                porro asperiores minima? Ab minus, optio error dolores neque nulla sit laborum labore nobis, architecto
                debitis ea dicta sequi temporibus beatae fugiat dolorum. Omnis distinctio dolor cum quo sed consequatur!
                Iusto ad iste aperiam ratione nihil ex atque reiciendis repellat laudantium quisquam, perferendis
                asperiores
                in cupiditate, est, mollitia natus neque labore minus. Animi aperiam est accusantium molestias libero
                aspernatur ex voluptate rerum voluptatem repellat officiis omnis cumque, eveniet tempore dolor
                doloremque
                quibusdam, id soluta beatae ut non perferendis! Ipsam a repudiandae quae fuga, eius accusamus
                praesentium
                dolore reiciendis maxime, perferendis ad neque quod accusantium. Architecto repellat minus eum quidem
                molestiae consequatur! Vitae deleniti ab ducimus at. Libero qui architecto debitis repudiandae magni
                praesentium maiores ut excepturi, alias, vel eveniet. Eaque enim, nulla laudantium numquam vero amet
                perferendis omnis dolor aut cum exercitationem? Vero, temporibus sunt magnam alias voluptates aspernatur
                voluptas accusantium ducimus nisi unde quam provident sequi perferendis ullam error praesentium veniam
                deleniti tenetur distinctio consequatur velit. Eaque ratione nulla assumenda recusandae omnis dolores
                praesentium. Qui, sequi repudiandae illo quo numquam molestiae corporis sed non tempora delectus magnam
                quas
                quasi expedita assumenda inventore vel beatae sunt optio, culpa ratione. Ad, debitis! Praesentium,
                voluptas
                sunt?</p>
        </transition>
    </div>
</template>

<style>
.fade-enter-from {
    opacity: 0;
}

.fade-enter-active {
    transition: opacity 3s ease;
}

.fade-leave-to {
    opacity: 0;
}

.fade-leave-active {
    transition: opacity 3s ease;
}
</style>